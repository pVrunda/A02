# A02

Installing and Setting up Git:
  1. Download the latest version of Git on your laptop using the following link: https://git-scm.com/downloads
  2. Run the installer and complete the download process.
  3. Open the terminal and set up your account

 Creating GitHub Account:
  1. Go to the following website to create the account: https://github.com
  2. Click on "sign up" and follow the direction to create the account.

Creating a repository:
  1. Once you are logged into your GitHub account, click on "+" icon on the upper right corner and Click on "New repository"
  2. Fill out the following information: Repository name, description, privacy setting.
  3. Click on "Create repository" to create a repository

Cloning a repository:
  1. On Github open up the repository you want to clone.
  2. Click the "code" button, and then copy the URL provided.
  3. On Git, open up the terminal.
  4. Navigate to where you want to clone. And write the following command: git clone <Insert URL>

Creating a branch:
  1. Use the following code to create a new branch: git checkout -b <name-of-the-branch>

How to push changes to GitHub:
  1. Use the following code to push the changes you made: git push origin <name-of-the-branch>

How to pull changes:
  1. To pull changes from the remote repository; use the following code: git pull origin <name-of-the-branch>



Glossary:

  Branch - A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes. 
  
  Clone - Is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synched when you're online. 
  
  Commit - A commit or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID ("SHA" or "harsh") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made. 
  
  Fetch - When you use "git fetch", you're adding changes from the remote repository to your local working branch without committing them. Unlike "git pull", fetching allows you to review changes before committing them to your local branch.
  
  GIT - Is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of. 
  
  Github - Is a platform for hosting and collaborating on Git repository. 
  
  Merge - Merging takes the changes from one branch (in the same repository or a from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the Github.com web interface if there are no conflicting changes, or can always be done via the command line.
  
  Merge Conflict - a difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches. 
  
  Push - To push means to send your committed changes to a remote repository on GitHub.com. For instance, id you change something locally, you can push those changes so that others may access them.
  
  Pull - When you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. 
  
  Remote - This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced. 
  
  Repository - It is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.

Link used for Glossary: https://docs.github.com/en/get-started/quickstart/github-glossary

References: 

https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account

https://docs.github.com/en/get-started/using-git/about-git



