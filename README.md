# CircleCI Tutorial
This is a very basic and simple tutorial on how to set up a Continuous Integration (CI) pipeline using CircleCI with a GitHub repository. The goal is to help you get started with automating your CI process using CircleCI.

## Prerequisites
Before you begin, ensure you have the following:
* A GitHub account.
* A GitHub repository where you'll configure the CI pipeline.
* Basic understanding of Git and YAML file structure.
* Account on CircleCI.

## Repository Structure
Here’s a quick overview of the structure of this GitHub repository:
```
.circleci/
  └── config.yml
README.md
main.py
tests.py
```
* .circleci/: This directory contains the config.yml file, which is the configuration file that defines the steps for your CircleCI pipeline.
* README.md: The file you are currently reading. It provides an overview of the project and the steps to set up CircleCI.
* main.py: This is your main application file. You can replace this with your actual code.
* tests.py: This file contains test cases for your application. CircleCI will automatically run these tests as part of the CI pipeline.

Now that you understand the directory structure, let’s dive into creating a CI pipeline and linking your GitHub repository to CircleCI.

1. **Go to CircleCI:**
   - Visit the [CircleCI website](https://app.circleci.com/home/).

2. **Sign Up / Sign In:**
   - If you don’t have an account, sign up using your GitHub credentials.
   - If you already have an account, sign in.

3. **Create a New Organization:**
   - If this is your first time setting up a project, you may need to create a new organization.
   - Follow the prompts to create and name your organization.

4. **Create a New Project:**
   - Click on the “Projects” tab from the CircleCI dashboard.
   - Click the “Set Up Project” button to start setting up a new project.

5. **Name Your Project:**
   - Enter a name for your project.

6. **Choose a Repository:**
   - Select your repository provider. For this tutorial, choose **GitHub**.
   - Authorize CircleCI with GitHub if you haven’t already.
   - Select the repository you want to link from the list of your GitHub repositories.

7. **Automatic Configuration Detection:**
   - CircleCI will automatically detect the `.circleci/config.yml` file if it exists in your repository.
   - Review the configuration detected by CircleCI.

8. **Finish the Setup:**
   - Click on “Set Up Project” to complete the setup process.

9. **Check Commits:**
   - Go to your CircleCI project dashboard.
   - Select the branch you want to monitor for commits.

10. **Pipeline Trigger:**
    - When you commit any changes to the selected branch, CircleCI will automatically trigger a pipeline based on the configuration in your `config.yml` file.
    - You can view the progress and results of your pipeline on the CircleCI dashboard.

For additional details and advanced configuration options, refer to the [CircleCI documentation](https://circleci.com/docs/).
