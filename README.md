# Basic-Git-And-GitHub-Workflow


Objective
The objective of this assignment is to familiarize myself with the basic workflow of creating a GitHub repository, connecting it to a local folder, and making commits and pushes.

Requirements
A GitHub account.
Git installed on my local machine.
A code editor of my choice, I used  Visual Studio Code.
Steps
Task 1: Repository Setup
GitHub Repository Creation:
I logged in to my GitHub account.
I created a new repository on GitHub named "Basic-Git-And-GitHub-Workflow".
I initialized it with a README file.
Task 2: Local Setup
Local Folder Setup:

I created a new folder on my local machine named "Basic-Git-And-GitHub-Workflow".
I opened a vscode terminal and navigated to the created folder.


Git Initialization:

I initialized a new Git repository in my local folder.

git init
Connecting to GitHub:

I linked my local repository to the GitHub repository created in Task 1.

git remote add origin https://github.com/UWINTWALI/Basic-Git-And-GitHub-Workflow.git
Task 3: Making Changes
Create a File:

Inside my local folder, I created a new text file named home.txt.
I added a simple text message to the file.

Committing Changes:

I staged the changes.

git add home.txt
I committed the changes.

git commit -m "Add home.txt with a pro story"
Task 4: Pushing to GitHub
Pushing to GitHub:

I pulled the latest changes from the remote repository to avoid conflicts.

git pull origin main --rebase
I pushed the committed changes to my GitHub repository.

git push -u origin main
Task 5: Verification
Verify on GitHub:
I visited my GitHub repository in a web browser and confirmed that the hello.txt file and commit message are visible.
