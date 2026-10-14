# Git Branching and Team Collaboration

## 1. Project Overview

This repository is for our Git Branching and Team Collaboration lab. We created it to learn how Git and GitHub are used when working on the same project with another person.

During this lab, we will work with branches, commits, and pull requests. We will also practice merging changes, resolving merge conflicts, and using Git from the terminal.
## 2. Team Members

| Name | Student ID | GitHub Username          |
|---|---|--------------------------|
| Maist Iqbal | 72865 | [nabi-72865]             |
| Bhavika Chaudhary | 73586 | [bhavikachaudhary-73586] |

## 3. Objectives

- Create and manage a shared GitHub repository.
- Clone a repository to a local machine.
- Create and work with separate Git branches.
- Track changes using Git commits.
- Push local branches to GitHub.
- Pull and integrate changes made by a teammate.
- Create and review Pull Requests (PRs).
- Merge branches and integrate contributions.
- Practice identifying and resolving merge conflicts.
- Complete interactive exercises on Learn Git Branching.
- Understand how Git supports teamwork and collaborative software development.

## 4. Technologies and Tools

- Git
- GitHub
- Terminal / Command Line
- Visual Studio Code
- [Learn Git Branching](https://learngitbranching.js.org/)

## 5. Branching Strategy

The team uses separate branches to work independently and safely integrate changes.

| Branch | Purpose |
|---|---|
| `main` | Contains the integrated project |
| `maist-work` | Contains Maist Iqbal's contributions |
| `bhavika-work` | Contains Bhavika Chaudhary's contributions |

Each team member makes changes on their own branch, commits the changes, and pushes the branch to GitHub. Pull Requests are then created so that the other team member can review the changes before merging them into `main`.

## 6. Git Commands Practiced

### Clone the repository

```bash
git clone <https://github.com/bhavikachaudhary-73586/IT_teamElective.git>
cd <https://github.com/bhavikachaudhary-73586/IT_teamElective.git>
```

### Check the repository status

```bash
git status
```

### Create and switch to a new branch

```bash
git checkout -b mi_branch
git checkout -b bc_branch
```

### Stage and commit changes

```bash
git add .
git commit -m ""
```

### Push a branch to GitHub

```bash
git push -u origin mi_branch
```

### Fetch changes from GitHub

```bash
git fetch origin
```

### Pull changes from the main branch

```bash
git pull origin main
```

### Merge another branch

```bash
git merge 
```

### View branches

```bash
git branch
git branch -a
```

### View commit history

```bash
git log --oneline --graph --all
```

### Compare changes

```bash
git diff
```

## 7. Pull Requests and Code Review

Pull requests allow us to check each other's work before adding it to the main branch.

Our workflow is:

- Create or switch to our own branch.
- Make changes to the project.
- Commit the changes.
- Push the branch to GitHub.
- Open a pull request targeting main.
- Let the other team member review the changes.
- Fix any issues if needed and merge the pull request.

This gives both team members a chance to contribute and understand each other's work.

## 8. Merge Conflict Resolution

A merge conflict can happen when two branches contain different changes to the same part of a file and Git cannot combine them automatically.

To practice resolving conflicts, we can make changes to the same line of a file on two separate branches. When we merge the branches, Git may ask us to resolve the conflict manually.

We then need to check both versions, decide what the final content should be, save the file, and commit the resolution.
## 9. Learn Git Branching

The team will use [Learn Git Branching](https://learngitbranching.js.org/) to practice Git concepts interactively.

Topics include:

- Basic Git commands
- Branch creation and switching
- Branch merging
- Rebasing
- Remote repositories
- Understanding commit history

The commands and concepts learned through these exercises will also be practiced in the shared GitHub repository.

## 10. Conclusion

Through this lab, we will learn how to use Git and GitHub when working with another person. We will practise making changes on separate branches, sharing our work, reviewing pull requests, and resolving merge conflicts.

These skills will be useful for future programming projects where several people need to work on the same codebase.