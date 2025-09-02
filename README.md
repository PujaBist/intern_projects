# intern_projects
### 1.What is Version Control?
##### Version Control is a system that helps developers track and manage changes to files (especially code) over time.
##### It allows multiple people to work on the same project without overwriting each other’s work.
##### Think of it as a "time machine" for your code – you can go back to earlier versions if something goes wrong.
#### 2. Why Use Version Control?
##### Track Changes – See what changed, who changed it, and when.
##### Collaboration – Multiple developers can work on the same project.
##### Backup – Your code history is safely stored.
##### Restore – Easily revert to previous versions if you make a mistake.
##### Branching & Merging – Work on new features without affecting the main project.

<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/52f2fe1c-39d7-42c7-a61e-023b08fa4d8c" />

### Types of Version Control
#### 1. Local Version Control
##### Stores versions on your local machine.
#### 2.  Centralized Version Control (CVCS)
##### A single server stores all code versions.
#### 3. Distributed Version Control (DVCS)
##### Every developer has a full copy of the repository.
#### Popular Version Control Systems


### Git
##### Git is the most popular Distributed Version Control System (DVCS).
##### It helps developers track changes, collaborate, and manage code history in software projects.
#####  With Git, every developer has a full copy of the project repository (not just the latest version).

## GitHub
### 📌 Definition
##### GitHub is a cloud-based hosting service for Git repositories.
##### It provides a web interface to store, share, and collaborate on projects using Git.
#####  Think of Git as the engine, and GitHub as the car with a nice dashboard.

### 🎯 Key Features of GitHub
##### Remote Repository Hosting – Store your Git repos online.
##### Collaboration – Work with teams using pull requests, issues, and discussions.
##### Version Control – Powered by Git under the hood.
##### Code Review – Review code changes before merging.
##### Project Management – Built-in tools (projects, issues, milestones).
##### Actions (CI/CD) – Automate testing, deployment, etc.
##### Open Source Community – Millions of public repositories to learn and contribute.

### Benefits of GitHub
##### Central place for code collaboration.
##### Free hosting for public repos.
##### Integration with tools (Slack, Jira, CI/CD).
##### Popular in open-source development.

### GitLab
#### 📌 Definition
##### GitLab is a web-based DevOps platform that provides Git repository hosting and a full set of tools for the software development lifecycle (SDLC).
##### Like GitHub, it uses Git under the hood, but it also has built-in CI/CD pipelines, project management, and deployment features.

#### 🎯 Key Features of GitLab
##### Git Repository Hosting – Manage and share your Git projects.
##### Collaboration Tools – Issues, merge requests, wikis, code review.
##### CI/CD Pipelines – Automate build, test, and deployment inside GitLab.
##### Project Management – Milestones, Kanban boards, roadmaps.
##### Security & Monitoring – Built-in security scanning and monitoring.
##### Self-Hosted Option – Can run GitLab on your own server (unlike GitHub which is mostly cloud-based).
##### DevOps in One Platform – Source code + CI/CD + project management in one place.



### Pre-commit hooks
#### 1. Definition
##### A pre-commit hook is a script that runs automatically before a commit is created in Git.
##### It ensures that only clean, valid, and properly formatted code is committed
#### 2. Why Use Pre-commit Hooks?
##### Prevent committing code with syntax errors.
##### Maintain consistent coding style (formatting, indentation).
##### Run tests or linters before allowing a commit.
##### Stop accidental commits of large files or secrets.
##### Ensure commit messages follow rules (when used with other hooks).
