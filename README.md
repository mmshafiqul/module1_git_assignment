# Module 1 Git Assignment
This is my assignment for learning Git and GitHub.

## DevOps Learning Project

This project is part of a hands-on learning exercise to understand the fundamentals of **DevOps** and **version control using Git and GitHub**. 

## Objectives

- Learn how to **initialize a Git repository** and make commits.
- Understand **branching and merging** workflows.
- Practice **creating pull requests** on GitHub.
- Gain familiarity with collaborative development practices.
- Explore automation and CI/CD concepts for future modules.

## Project Structure

- `README.md` – Project description and instructions.
- `hello.txt` – Sample file created on the `dev` branch to demonstrate branching and merging.

---

## Step-by-Step Commands for the Assignment

### 1. Initialize a Git repository
```bash
git init


### 2. Create README.md and commit initial changes
echo "# DevOps Learning Project" > README.md
git add README.md
git commit -m "Initial commit: Add README.md with project description"

### 3. Add remote GitHub repository and push main
git remote add origin https://github.com/mmshafiqul/module1_git_assignment.git
git branch -M main
git push -u origin main

### 4. Create a new branch dev and switch to it
git checkout -b dev

### 5. Create hello.txt with a descriptive message
echo "Hello! This file is part of the DevOps learning project. It demonstrates creating a new file in the 'dev' branch and committing changes using Git." > hello.txt

### 6. Stage and commit hello.txt
git add hello.txt
git commit -m "Add hello.txt in dev branch with a descriptive message for the DevOps learnin

### 7. Push the dev branch to GitHub
git push -u origin dev

### 8. Update local main branch after merge
git checkout main
git pull origin main
