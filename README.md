```markdown
# Git Assignment - briggyx
```

> a. What is an _issue_?

In Git, an issue is a tool used to track tasks, enhancements, bugs, or any other type of discussion related to the repository.

- **Bug Tracking**: Used to report and track bugs or problems in the software.
- **Feature Requests**: Allows users to suggest new features or enhancements.
- **Task Management**: Breaks down large tasks into smaller, manageable pieces.
- **Documentation and Discussion**: Provides a space for discussion and feedback on specific topics.
- **Labels and Milestones**: Categorizes and prioritizes issues with labels and organizes them under milestones.
- **Assignment and Collaboration**: Assigns issues to specific contributors for resolution, facilitating collaboration.
- **Integration with Commits and Pull Requests**: Links issues with commits and pull requests for better traceability of changes.

> b. What is a _pull request_?

A pull request (often abbreviated as PR) is a feature that allows developers to notify team members that they have completed some work on a branch and would like it to be reviewed, discussed, and potentially merged into another branch, typically the main branch of the repository.

- **Code Review**: Allows team members to review and provide feedback on proposed changes.
- **Proposing Changes**: Used to propose changes from a feature branch to a main branch.
- **Branch Management**: Helps manage separate feature branches to avoid disrupting the main codebase.
- **Continuous Integration**: Automatically runs tests and checks to ensure new code doesn’t break existing functionality.
- **Collaboration**: Facilitates discussion and collaboration among team members on code changes.
- **Documentation**: Acts as a record of what changes were made, why, and how they were reviewed.
- **Automated Merging**: Once approved, allows for automated merging of changes into the main branch.
- **Open Source Contributions**: Provides a mechanism for outside contributors to suggest changes to a project.

> c. How do I open up a _pull request_?

1. **Navigate to Your Repository on GitHub**: Open your repository page on GitHub.

2. **Go to the "Pull Requests" Tab**: Click on the **"Pull requests"** tab at the top of the page.

3. **Click "New Pull Request"**: Select the green **"New pull request"** button.

4. **Choose Branches to Compare**: Select the base branch (e.g., `main`) and your feature branch (e.g., `assignment`) to compare changes.

5. **Review Changes**: Check the differences between the branches to ensure everything looks correct.

6. **Add Title and Description**: Provide a descriptive title and a detailed description of the changes in the pull request.

7. **Create the Pull Request**: Click the **"Create pull request"** button.

8. **Optional: Assign Reviewers and Add Labels**: You can assign reviewers and add labels if needed.

> d. Give me a step by step guide on how to add someone to your repository.

1. **Go to Your Repository on GitHub**: Open your repository in GitHub.

2. **Navigate to "Settings"**: Click the **"Settings"** tab at the top of the page.

3. **Select "Collaborators and teams"**: In the sidebar, click **"Collaborators and teams"** under the "Access" section.

4. **Click "Add People"**: Press the **"Add people"** button.

5. **Enter Username or Email**: Type the GitHub username or email of the person you want to add.

6. **Select the User**: Choose the correct user from the dropdown list.

7. **Set Permissions**: Choose the appropriate access level (Read, Triage, Write, Maintain, Admin).

8. **Send the Invitation**: Click **"Add to repository"** to send an invitation.

9. **Wait for Acceptance**: The user must accept the invitation to gain access.

> e. What is the difference between `git` and `GitHub`?

**Git** is a version control system that tracks changes to files and manages source code history locally. 

**GitHub** is a web-based platform that hosts Git repositories, allowing for collaboration, remote access, and additional features like pull requests, issue tracking, and project management. 

In short, Git is the tool, while GitHub is a service for using Git collaboratively online.

> f. What does `git diff` do?

`git diff` shows the differences between files in your Git repository. It compares changes that have not been staged for commit, the changes between commits, or changes between the working directory and a particular commit. It highlights what has been added, modified, or deleted.

> g. What is the `main` branch?

The **`main`** branch is the default primary branch in a Git repository where the source code for the project is considered stable and production-ready. It is the central branch that developers typically use to integrate completed features or bug fixes from other branches. The `main` branch replaces the `master` branch in many projects as the default name, following a shift toward more inclusive terminology.

> h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the `main` branch?

No, you should not directly push changes to the `main` branch, especially in a collaborative environment. Instead, you should:

1. **Create a new branch** for your feature or fix.
2. **Work on that branch** and make your changes.
3. **Open a pull request** to merge your changes into the `main` branch after review and approval.

This workflow helps maintain the stability of the `main` branch and ensures that all changes are reviewed before being merged.