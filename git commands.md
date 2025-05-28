# Git Workflow – Feature Branch

## 1. Update from `main` first

```bash
git checkout main
git pull origin main
```

---

## 2. Create a new feature branch

```bash
git checkout -b feature/your-feature-name
```

---

## 3. Make changes and commit

```bash
git add .
git commit -m "Describe what you changed"
```

---

## 4. Push the branch to GitHub

```bash
git push
# or for first push:
git push -u origin feature/your-feature-name
```

---

## 5. Create a Pull Request (PR) via GitHub GUI

1. Go to the repository on GitHub
2. You should see a green button: **"Compare & pull request"**
3. Click it
4. Fill in a title and description
5. Click **"Create Pull Request"**

---

## 💻 Clone the repository (first time)

```bash
git clone https://github.com/TBoneMendez/cool-data-tools.git
```
