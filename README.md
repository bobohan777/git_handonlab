# Step-by-Step Guide for HOL-Assignment Git Practice 

Preparation:
Git Hosting Platform Account: Create an account on GitHub or another platform, if you haven't already.

Install Git: Ensure Git is installed on your local machine. Download from https://git-scm.com/downloads.'

## Step 1: Initialize Repository and Basic Setup

New Repository: On your platform, create a new repository named "HOL-Assignment".

Clone Repository: Open a terminal and clone the repository to your local machine using the provided URL.

```Bash
git clone <repository_url>
```

Configure Git: Run these commands to configure your name and email:

```Bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

Step 2: Branching and Committing Changes
Feature Branch: Create a new branch called "feature/new-feature" based on "main":
Bash
git checkout -b feature/new-feature
Use code with caution.
Create and Add File: Create "feature.txt" with some content (e.g., "This is a new feature").
Stage Changes: Stage the file for the next commit:
Bash
git add feature.txt
Use code with caution.
Commit Changes: Commit with a descriptive message:
Bash
git commit -m "Added new feature file (feature.txt)"
Use code with caution.
Push Branch: Push your changes to the remote repository:
Bash
git push origin feature/new-feature
Use code with caution.
Step 3: Pull Request and Merge
Create Pull Request: On your platform, create a pull request to merge "feature/new-feature" into "main".
Review and Merge: Review your own pull request, address any comments, and merge when ready.
Step 4: Collaboration
Invite Collaborator: Share the repository link to invite your classmate/colleague.
Collaborator Setup: Ask them to clone the repository and create a dedicated branch (e.g., "collab/my-contribution").
Assign Task: Give your collaborator a task (e.g., adding a new file).
Review and Merge Pull Request: Review their pull request and merge it into "main" after approval.
Step 5: Documentation and Submission
Create README.md: Create a file named "README.md" in the root directory.
Document Project: In the README, write a short project description, purpose, and getting-started instructions.
Collaboration Guidelines: Include information for collaborators on contributing and reporting issues.
Submit URL: Submit the URL of your Git repository containing all completed tasks.