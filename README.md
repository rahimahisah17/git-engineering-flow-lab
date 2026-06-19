> 📖 A detailed walkthrough of this project is available on Dev.to: https://dev.to/rahimah_dev/git-engineering-workflow-1-2l0k
>
> # Git Engineering Workflow Lab

## Overview

This repository was created as a hands-on lab to practice and understand a complete Git and GitHub engineering workflow. The project simulates how software teams collaborate on features, review code, and merge changes into a production-ready branch.

The objective was not to build a complex application but to gain practical experience with the tools and processes used in modern software development.

---

## What Was Accomplished

### 1. Repository Creation

A GitHub repository was created to serve as the central location for storing project files and tracking version history.

### 2. Repository Cloning

The repository was cloned to a local machine, creating a working copy that could be modified without directly affecting the remote repository.

### 3. Feature Branch Creation

A dedicated feature branch named `feature/add-login-button` was created. This allowed development work to be isolated from the `main` branch, ensuring that the production-ready code remained stable.

### 4. Code Changes and Commit

A sample login-related file was added to simulate feature development. The changes were staged and committed using Git, creating a snapshot that could be tracked and reviewed later.

### 5. Push to GitHub

The feature branch was pushed to GitHub, making the changes available remotely and ready for collaboration.

### 6. Pull Request Creation

A Pull Request (PR) was opened to propose merging the feature branch into the `main` branch. This mimics the workflow used by professional development teams.

### 7. Code Review

The Pull Request was reviewed using GitHub CLI commands. This step demonstrated how developers inspect and validate changes before they are merged.

### 8. Merge to Main

The Pull Request was merged into the `main` branch using a squash merge strategy. This combined all feature work into a single clean commit and kept the project history organized.

### 9. CI/CD Introduction

A basic GitHub Actions workflow was added to introduce Continuous Integration concepts. This demonstrated how code changes can automatically trigger validation and deployment pipelines.

---

## Skills Practiced

Throughout this project, the following skills were developed:

* Git fundamentals
* Branching strategies
* Commit management
* Remote repository management
* Pull Request workflow
* Code review process
* Merge strategies
* GitHub CLI usage
* Basic CI/CD concepts
* GitHub Actions fundamentals

---

## Tools Used

* Git
* GitHub
* GitHub CLI (gh)
* Visual Studio Code
* GitHub Actions

---

## Learning Outcome

By completing this lab, I gained practical experience with the end-to-end Git workflow used by modern software engineering teams. The exercise reinforced the importance of version control, collaboration, code review, and automation in delivering reliable software.
