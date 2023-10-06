# Week 1 Solution

**1. Setup:**

- **Set up Git:**
  - Download and install Git from the official website: <https://git-scm.com/downloads>.
  - Open your terminal or command prompt.
  - Configure Git with your name and email address:

       ```bash
       git config --global user.name "Your Name"
       git config --global user.email "your@email.com"
       ```

- **Create a GitHub Account:**
  - Go to <https://github.com/> and sign up for a free GitHub account.

- **Fork the Starter Repository:**
  - Go to the GitHub repository you want to contribute to (the "Week-1").
  - Click the "Fork" button in the top right corner of the repository page. This will create a copy of the repository under your GitHub account.

- **Clone Your Fork:**
  - Open your terminal or command prompt.
  - Clone your forked repository to your local machine using:

       ```bash
       git clone <your-fork-repository-URL>
       ```

**2. Initial Commit:**

- **Create a Folder:**
  - Create a folder on your local machine where you want to store your project.

- **Create an HTML File:**
  - Inside the project folder, create an HTML file (e.g., `index.html`) using a text editor or code editor of your choice.
  - Add some basic HTML content to the file.

- **Initialize a Git Repository:**
  - Open your terminal or command prompt.
  - Navigate to your project folder using the `cd` command.
  - Ensure the current directory has a `.git` folder by running:

       ```bash

       ```bash
       git status
       ```

  - if it does not have one, make sure you are inside the folder that appeared when you cloned your forked repo!

- **Add and Commit:**
  - Add the HTML file to the Git repository:

       ```bash
       git add index.html
       ```

  - Commit the changes with a meaningful message:

       ```bash
       git commit -m "Initial commit"
       ```

**3. Branching:**

- **Create a New Branch:**
  - Create a new branch named "feature":

       ```bash
       git branch feature
       ```

- **Switch to the New Branch:**
  - Switch to the "feature" branch:

       ```bash
       git checkout feature
       ```

- **Make Changes:**
  - Make changes to the `index.html` file in the "feature" branch using a text editor.

**4. Merging:**

- **Switch Back to Main:**
  - Switch back to the main branch:

       ```bash
       git checkout main
       ```

- **Merge the Branch:**
  - Merge the "feature" branch into the main branch:

       ```bash
       git merge feature
       ```

**5. Push to Your Fork on GitHub:**

- **Push to Your Fork:**
  - Push your local repository to your fork on GitHub:

       ```bash
       git push origin main
       ```

**6. Create a Pull Request:**

- **GitHub Pull Request:**
  - Go to your forked repository on GitHub in a web browser.
  - Click on the "Pull Requests" tab.
  - Click the "New Pull Request" button.
  - Select the base repository's "main" branch as the base branch and your fork's "main" branch as the compare branch.
  - Add a description for the Pull Request.
  - Review the changes and create the Pull Request.

**7. Collaboration (Optional):**

- **Invite Collaborators:**
  - In your forked GitHub repository, go to "Settings."
  - Click on "Collaborators" on the left sidebar.
  - Invite a friend by entering their GitHub username or email address.

- **Collaborate:**
  - Your friend can fork your repository to their GitHub account.
  - They can clone their forked repository to their local machine and create a branch, make changes, commit, and push to GitHub.
  - Your friend can then create a Pull Request from their fork to your repository.
