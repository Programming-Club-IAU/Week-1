# Git and github introduction

- [Git Tutorial (w3schools.com)](https://www.w3schools.com/git/default.asp)
- [How to Use Git and GitHub – Introduction for Beginners (freecodecamp.org)](https://www.freecodecamp.org/news/introduction-to-git-and-github/)
- [Learn Git Branching](https://learngitbranching.js.org/) (Interactive tutorial)
- [Git - Basic Branching and Merging (git-scm.com)](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- [Pull Requests in VS Code - YouTube](https://www.youtube.com/watch?v=LdSwWxVzUpo)

## Project: Create a Simple Website

Description: You will create a simple static website with a few pages and use Git and GitHub to manage the project's version control.
Tasks:

1. Setup:
   - Set up Git on your local machine if you haven't already.
   - Create a GitHub account if you don't have one.
   - Create a new GitHub repository (let's call it "SimpleWebsite").
2. Initial Commit:
   - Create a folder on your local machine for the project.
   - Inside the folder, create an HTML file (e.g., index.html) and add some basic content.
   - Initialize a Git repository in the project folder using the git init command.
   - Add the HTML file to the repository using git add.
   - Commit the changes using git commit.
3. Branching:
   - Create a new branch named "feature" using git branch feature.
   - Switch to the "feature" branch using git checkout feature.
   - Make some changes to the HTML file in the "feature" branch, like adding a new page or modifying existing content.
4. Merging:
   - Switch back to the main branch using git checkout main.
   - Merge the changes from the "feature" branch into the main branch using git merge feature.
   - Remote Repository:
   - Link your local repository to the GitHub repository you created earlier using git remote add origin `<repository URL>`.
   - Push your local repository to GitHub using git push -u origin main.
5. Pull Requests:
   - Go to the GitHub repository.
   - Create a new Pull Request (PR) to merge the "feature" branch into the main branch.
   - Add a description for the PR.
   - Review the changes and create the PR.
6. Collaboration (Optional):
   - Invite a friend to collaborate on the project by adding them as a collaborator on the GitHub repository.
   - Have your friend clone the repository, create a branch, make changes, and create a Pull Request as well.
   - Review and merge their changes into the main branch.
  