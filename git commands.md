# Git Workflow – Feature Branch

Use this workflow to create, push, and merge feature branches using Git and GitHub.

## 1. Update from `main` first

```bash
git checkout main
git pull origin main
```

## 2. Create a new feature branch

```bash
git checkout -b feature/your-feature-name
```

## 3. Make changes and commit

```bash
git add .
git commit -m "Describe what you changed"
```

## 4. Push the branch to GitHub

```bash
git push
# Or, for first-time push:
git push -u origin feature/your-feature-name
```

## 5. Create a Pull Request (PR) via GitHub

1. Go to the repository on GitHub
2. Look for the green button: **"Compare & pull request"**
3. Click it
4. Enter a clear title and description
5. Click **"Create Pull Request"**

---

# Git Commands – Create a New Repository from the CLI

To create and push a new repository directly from the command line using GitHub CLI (`gh`):

## 1. Initialize a new Git repository

```bash
git init
git branch -M main
git add .
git commit -m "Initial commit"
```

## 2. Create the GitHub repository and push

```bash
gh repo create your-repo-name --public --source=. --remote=origin --push
```

Replace `your-repo-name` with your desired repository name.

- Use `--private` if you want the repository to be private.
- `--source=.` points to the current directory.
- `--push` automatically pushes your main branch after creation.

After completing these steps, your project is live on GitHub and ready for collaboration.

---

## Clone a Repository

To clone a repository to your local machine:

```bash
git clone https://github.com/TBoneMendez/cool-data-tools.git
```
