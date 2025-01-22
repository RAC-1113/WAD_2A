1. Project Setup

Create a GitHub Repository:

Log in to your GitHub account.
Click on the "New" button and create a new repository.
Give your repository a name and a brief description.
Important: Choose "Initialize this repository with a README" if you want to start with a basic README file.
Click "Create repository."
Local Project Setup:

Create a local folder for your project.
Open your terminal or command prompt and navigate to the project folder using the cd command.

2. Initialize Git

In your terminal, run the following command to initialize a Git repository in your local project folder:
  git init
This creates a hidden .git folder within your project directory, which contains all the necessary files for Git to track changes.

3. Stage Changes

Add files to staging area: Use the git add command to add specific files or all files in your project to the staging area.
To add all files:
  git add .

4. Commit Changes

Create a commit: Use the git commit command to create a snapshot of the staged changes with a descriptive message.
  git commit -m "Initial commit"

Replace "Initial commit" with a meaningful message that describes the changes you made.

5. Connect to Remote Repository

Get the remote repository URL: Copy the HTTPS or SSH URL of your GitHub repository from the repository's page.
Add remote: Use the git remote add command to connect your local repository to the remote GitHub repository.
  git remote add origin <remote_repository_url>
Replace <remote_repository_url> with the actual URL.

6. Push Changes

Push to remote: Use the git push command to upload your local commits to the remote repository.
  git push -u origin main
Replace main with the name of the branch you want to push to (usually main or master).
The -u flag sets the upstream branch, so you can use git push without specifying the branch name in the future.

7. Verify

Check GitHub: Go to your GitHub repository page. You should see your commits and files reflected in the repository.
