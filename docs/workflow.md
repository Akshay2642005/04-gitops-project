# Git Workflow Documentation

## Step 1: Initialize Repo
```bash
git init
git remote add origin https://github.com/<your-username>/devops-git-project.git
```

## Step 2: Branching
```bash
git checkout -b dev
git checkout -b feature/<feature-name>
```

## Step 3: Commit Messages
- Use short, clear commit messages
- Example: `Add login API endpoint`

## Step 4: Pull Requests
- Always merge via PR
- Review before merging

## Step 5: Tags
- Tag releases: `git tag v1.0.0`
```
