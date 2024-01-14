# learnable-git

Git and Github task from learnable

# Table of Contents

- [Introduction to Git and GitHub](#introduction-to-git-and-github)

  - [Version Control](#version-control)
    - [Local Repository](#local-repository)
    - [Commits](#commits)
    - [Branches](#branches)
    - [Merging](#merging)

- [Difference between Git and Github](#difference-between-git-and-github)

  - [Git](#git)
  - [GitHub](#github)

- [GitHub Alternatives](#github-alternatives)

- [Git Fetch vs Git Pull](#git-fetch-vs-git-pull)

  - [Git Fetch](#git-fetch)
  - [Git Pull](#git-pull)

- [Git Rebase](#git-rebase)

  - [Simple Explanation](#simple-explanation)
  - [Command](#command)

- [Git Cherry-pick](#git-cherry-pick)
  - [Simple Explanation](#simple-explanation-1)
  - [Command](#command-1)

## Version Control

Version control is a system that helps you track changes in your project's codebase over time. Git is a popular version control system.

1. ### **Local Repository:**

   - Your project is a collection of files and folders on your computer.
   - Git helps you create a "repository" to track changes in this project.

2. ### **Commits:**

   - As you make changes to your project, Git lets you take "snapshots" of your project's state, called "commits."

3. ### **Branches:**

   - Git allows you to create different "branches" to work on separate features or changes without affecting the main project.
   - For example, you might have a branch for a new feature and another branch for fixing a bug.

4. ### **Merging:**
   - Once you're satisfied with the changes in a branch, you can "merge" that branch back into the main project.
   - Merging combines the changes from one branch into another.

## Difference between Git and Github

### Git

Git is a distributed version control system that allows developers to track changes in their codebase. It operates locally on your machine and enables you to create branches, commit changes, and manage the version history of your project.

### GitHub

GitHub is a web-based platform that leverages Git for collaborative software development. It provides a centralized location to host Git repositories online, facilitating collaboration among team members.

In summary, Git is the version control system that operates locally, while GitHub is a web-based platform that uses Git to enable collaborative development and provides additional tools for project management.

## GitHub Alternatives

1. GitLab

2. Bitbucket

3. SourceForge

## Git Fetch vs Git Pull

### Git Fetch

- `git fetch` is used to download changes from the remote repository to your local repository.
- It retrieves any new branches or changes in existing branches from the remote but does not automatically merge them into your working directory.
- After fetching, you need to use additional commands like `git merge` or `git rebase` to integrate the changes into your local branches.

### Git Pull

- `git pull` is a combination of two actions: `git fetch` followed by `git merge`.
- It fetches changes from the remote repository and automatically merges them into the current branch in your working directory.
- `git pull` is a convenient way to update your local branch with the changes from the remote repository in a single command.

In summary, while both `git fetch` and `git pull` update your local repository with changes from the remote, `git fetch` only downloads the changes, leaving them unmerged, while `git pull` automatically incorporates the changes into your working directory.

## Git Rebase

### Simple Explanation

- `git rebase` is a command in Git used to reapply commits on top of another base commit.
- It allows you to modify the commit history, making it appear as if the changes were made on top of the latest codebase.
- Useful for creating a cleaner and more linear commit history, especially when working with feature branches.

### Command

The basic syntax for `git rebase` is:

```bash
git rebase <base>
```

## Git Cherry-pick

### Simple Explanation

- `git cherry-pick` is a command in Git used to apply a specific commit from one branch to another.
- It allows you to select and incorporate changes from a commit without merging the entire branch.
- Useful for applying specific bug fixes or features to different branches.

### Command

The basic syntax for `git cherry-pick` is:

```bash
git cherry-pick <commit-hash>
```
