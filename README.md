# Introduction:
This guide will help you set up Git and GitHub, and walk you through the process of adding files to a GitHub repository using Git. Git is a version control system that lets you track changes to your files and collaborate with others. GitHub is a cloud-based platform that hosts Git repositories.

# Prerequisites:
Basic knowledge of command line/terminal usage
A GitHub account (sign up at github.com)
Setting Up Git

# Install Git:
Windows: Download and install Git from git-scm.com.
macOS: Install Git via Homebrew: brew install git.
Linux: Install Git via your package manager, e.g., sudo apt-get install git for Debian-based systems.

# Configure Git:
Open your terminal and set your Git username and email:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Setting Up a GitHub Repository:
Create a New Repository on GitHub
Go to your GitHub account and click the New button or navigate to github.com/new.
Enter a repository name, description (optional), and choose the repository's visibility (public or private).
Click Create repository.

# Cloning a Repository:
Clone the Repository to Your Local Machine
Copy the repository URL from GitHub (e.g., https://github.com/username/repository.git).
Open your terminal and run:
git clone https://github.com/username/repository.

# Navigate to the cloned repository:
cd repository

# Adding and Committing Files:
Add Files to Your Repository
Add the files you want to track in your repository.

## Use the following commands to stage and commit your changes:
git add .
git commit -m "Add initial files"

## Pushing Changes to GitHub:
Push Your Changes to GitHub
Push your local commits to the remote repository on GitHub:
git push origin main
Replace main with the name of your branch if it's different.

## Common Git Commands:
### Check Status:
git status
### View Commit History:
git log
### Create a New Branch:
git branch new-branch-name
### Switch to a Branch:
git checkout branch-name
### Merge a Branch:
git merge branch-name

# Conclusion
You've now set up Git and GitHub, cloned a repository, added files, committed changes, and pushed those changes to GitHub. This guide covered the basics, but Git and GitHub have many more features to explore. For more information, check out the Git documentation and GitHub Guides.
