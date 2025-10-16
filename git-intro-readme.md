# Introduction to Git and GitHub Assignment

## Objective
Learn the basics of Git version control and GitHub by cloning a repository, making changes, and pushing them back to GitHub.

## What You'll Learn
- How to clone a repository from GitHub
- How to make changes to files locally
- How to commit your changes
- How to push changes back to GitHub

## Prerequisites
- Git installed on your computer ([Download Git](https://git-scm.com/downloads))
- A GitHub account
- Basic command line knowledge

## Instructions

### Step 1: Clone the Repository
1. Open your terminal (Command Prompt, Git Bash, or Terminal)
2. Navigate to where you want to store the project:
   ```bash
   cd Documents
   ```
3. Clone this repository using the command:
   ```bash
   git clone <your-repository-url>
   ```
4. Navigate into the cloned repository:
   ```bash
   cd <repository-name>
   ```

### Step 2: Open and Edit the File
1. Open the `index.txt` file in your preferred text editor
2. Add your full name to the file
3. Save the file

### Step 3: Check Your Changes
1. In your terminal, check the status of your repository:
   ```bash
   git status
   ```
   You should see `index.txt` listed as modified

### Step 4: Stage Your Changes
1. Add the modified file to the staging area:
   ```bash
   git add index.txt
   ```

### Step 5: Commit Your Changes
1. Commit your changes with a descriptive message:
   ```bash
   git commit -m "Add my name to index.txt"
   ```

### Step 6: Push to GitHub
1. Push your changes back to GitHub:
   ```bash
   git push origin main
   ```
   (Note: If your default branch is `master` instead of `main`, use `git push origin master`)

### Step 7: Verify on GitHub
1. Go to your repository on GitHub
2. Check that your changes appear in the `index.txt` file
3. You should see your commit in the commit history

## Submission
Once you've pushed your changes to GitHub, your assignment is complete! Your instructor will be able to see your commits and changes in your repository.

## Common Issues and Solutions

**Problem**: "Permission denied" when pushing
- **Solution**: Make sure you're authenticated with GitHub. You may need to set up a personal access token or SSH key.

**Problem**: "Failed to push some refs"
- **Solution**: Someone else may have pushed changes. Try `git pull origin main` first, then push again.

**Problem**: Can't find Git command
- **Solution**: Make sure Git is installed and added to your system PATH.

## Resources
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

## Questions?
If you encounter any issues, please reach out to your instructor or check the course discussion board.

---
Good luck! 🚀