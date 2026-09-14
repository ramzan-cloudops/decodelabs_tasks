Objective

Practice Git and GitHub for version control by creating repositories, tracking changes, committing work, synchronizing with remote repositories, cloning repositories, and managing branches.

---

## 1. Git Repository Setup & Basic Workflow

### Objective
Practice initializing a Git repository, checking its status, staging changes, and creating commits.

### Commands

```bash
git init
git status
git add .
git commit -m "Add internship tasks"
```

- `git init` — Initializes a new Git repository.
- `git status` — Shows the current repository state and untracked or modified files.
- `git add .` — Stages all changes for the next commit.
- `git commit -m "Add internship tasks"` — Saves the staged changes in Git history with a commit message.

### Screenshot

<img width="870" height="500" alt="Git Repository Setup and Basic Workflow" src="YOUR-IMAGE-LINK-HERE" />

---

## 2. Remote Repository, Push & Pull

### Objective
Practice connecting a local Git repository with GitHub and synchronizing changes between the local and remote repositories.

### Commands

```bash
git branch -M main
git remote add origin git@github.com:ramzan-cloudops/decodelabs_tasks.git
git push -u origin main
git push origin main
git pull
```

- `git branch -M main` — Renames the current branch to `main`.
- `git remote add origin <repository-url>` — Connects the local repository to the GitHub remote repository.
- `git push -u origin main` — Uploads the local `main` branch to GitHub and sets the upstream branch.
- `git push origin main` — Pushes local changes to the remote `main` branch.
- `git pull` — Downloads and integrates changes from the remote repository.

### Screenshot

<img width="870" height="500" alt="Git Remote Push and Pull" src="YOUR-IMAGE-LINK-HERE" />

---

## 3. Git Clone

### Objective
Practice creating a local copy of an existing GitHub repository.

### Command

```bash
git clone https://github.com/ramzan-cloudops/devops-intern-final
```

- `git clone` — Downloads an existing GitHub repository to the local machine along with its Git history.

### Screenshot

<img width="870" height="500" alt="Git Clone" src="YOUR-IMAGE-LINK-HERE" />

---

## 4. Git Branching & Branch Management

### Objective
Practice creating, switching, viewing, and deleting Git branches to manage work separately from the main branch.

### Commands

```bash
git branch
git checkout decode
git branch decode
git checkout decode
git checkout -b master
git branch
git checkout main
git branch
git branch -d decode
git branch master
git branch -d master
```

- `git branch` — Lists the available local branches and shows the current branch.
- `git checkout decode` — Switches to the `decode` branch.
- `git branch decode` — Creates a new branch named `decode`.
- `git checkout -b master` — Creates and immediately switches to a new `master` branch.
- `git checkout main` — Switches back to the `main` branch.
- `git branch -d decode` — Deletes the `decode` branch.
- `git branch master` — Attempts to create a `master` branch. Git reports an error if the branch already exists.
- `git branch -d master` — Deletes the `master` branch.

### Screenshot

<img width="870" height="500" alt="Git Branching and Branch Management" src="YOUR-IMAGE-LINK-HERE" />

