# Git Branching and Team Collaboration

## 1. Project Overview

This repository was created for the Git Branching and Team Collaboration lab assignment. The purpose of this project is to gain practical experience with Git and GitHub, including version control, branching, commits, pull requests, merging, and resolving merge conflicts.

Both team members will actively contribute to the repository and practice collaborating on a shared project.

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

## 5. Repository Structure

```text
git-branching-lab/
├── README.md
├── student1.txt
├── student2.txt
└── conflict.txt
```

The files `student1.txt` and `student2.txt` can be used to demonstrate individual contributions, while `conflict.txt` can be used to practice resolving merge conflicts.

## 6. Branching Strategy

The team uses separate branches to work independently and safely integrate changes.

| Branch | Purpose |
|---|---|
| `main` | Contains the integrated project |
| `maist-work` | Contains Maist Iqbal's contributions |
| `bhavika-work` | Contains Bhavika Chaudhary's contributions |

Each team member makes changes on their own branch, commits the changes, and pushes the branch to GitHub. Pull Requests are then created so that the other team member can review the changes before merging them into `main`.

## 7. Git Commands Practiced

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
git switch -c mi_branch
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

## 8. Pull Requests and Code Review

Pull Requests are used to propose and review changes before they are merged into the main branch.

The workflow is:

1. Create a separate branch.
2. Make changes and commit them.
3. Push the branch to GitHub.
4. Open a Pull Request targeting `main`.
5. Ask the teammate to review the changes.
6. Discuss or correct any issues found during the review.
7. Merge the Pull Request after approval.

Both team members will create Pull Requests and review each other's contributions.

## 9. Merge Conflict Resolution

A merge conflict occurs when Git cannot automatically combine changes, for example, when two team members modify the same line of a file differently.

To practice resolving conflicts:

1. Create a shared file named `conflict.txt`.
2. Make different changes to the same line on separate branches.
3. Commit and push the changes from both branches.
4. Merge one branch into the other.
5. Open the conflicted file and review Git's conflict markers.
6. Edit the file to keep the agreed-upon final content.
7. Remove the conflict markers.
8. Stage, commit, and push the resolved changes.

## 10. Learn Git Branching

The team will use [Learn Git Branching](https://learngitbranching.js.org/) to practice Git concepts interactively.

Topics include:

- Basic Git commands
- Branch creation and switching
- Branch merging
- Rebasing
- Remote repositories
- Understanding commit history

The commands and concepts learned through these exercises will also be practiced in the shared GitHub repository.

## 11. Task Completion Checklist

- [ ] Create GitHub accounts containing student IDs in the usernames.
- [ ] Create a shared GitHub repository.
- [ ] Give both team members access to the repository.
- [ ] Clone the repository locally.
- [ ] Create separate branches for both students.
- [ ] Make and commit individual changes.
- [ ] Push both branches to GitHub.
- [ ] Pull or fetch changes made by the teammate.
- [ ] Create Pull Requests.
- [ ] Review the teammate's Pull Request.
- [ ] Merge Pull Requests.
- [ ] Create and resolve a merge conflict.
- [ ] Complete Learn Git Branching exercises.
- [ ] Practice the learned concepts in the shared repository.

## 12. Conclusion

This lab provides practical experience with Git and GitHub as collaborative version control tools. By completing the exercises together, both team members will develop an understanding of branching, committing, remote repositories, Pull Requests, code review, merging, and conflict resolution.

The project demonstrates how developers can work independently on different branches while collaborating to maintain a shared codebase.
