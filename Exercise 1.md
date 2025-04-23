## Homework Exercises: Version Control (Git & GitHub)

### Section 1: Terminology & Concepts

**1. Match the Term:** Match the following Git terms with their correct definitions.

- Repository
- Commit
- Branch
- Merge
- Staging Area
- Conflict

**Definitions:**

- A project folder tracked by Git.
- A snapshot of changes recorded in the Git history.
- A copy of your codebase for parallel development.
- Combines changes from different branches.
- A holding area for files before committing.
- Happens when two commits modify the same line.

---

### Section 2: Command Line Practice

**2. Git Commands Quiz:** Fill in the missing commands.

1. Initialize a new Git project: `git (init)`
2. Create a new branch called "feature-x": `git (branch or checkout -b) feature-x`
3. Stage all files: `git (add .) `
4. See changes that are staged: `git (status)`
5. Combine changes from feature-x to main: `git (mergre) feature-x`

---

### Section 3: GitHub Workflow

**3. Pull Request Scenario:**

You're working on a team project. You've added a new feature in a branch called `feature/login`. What are the steps to push it to GitHub and open a pull request?

List the steps one by one.

- git checkout feature/login
- git add .
- git commit -m "add new feature (login feature) to the project"
- git push origin feature/login

then i will open github and navigate to the repo, github suggest openning a pull request (Compare & pull request)

### Section 4: Best Practices

**4. Commit Messages Challenge:**

Write a clear and meaningful commit message for the following scenario:

"You added a responsive navbar component to your web application."

Bad Example: `update`  
Your Turn:

- git commit -m "add responsive navbar component to my project"
