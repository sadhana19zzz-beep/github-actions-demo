# GitHub Actions CI/CD Demo 🚀

## 📌 Overview
This project demonstrates a basic **Continuous Integration (CI) pipeline using GitHub Actions**.  
The workflow runs automatically whenever code is pushed to the `main` branch.

---

## ⚙️ CI/CD Workflow

Whenever changes are pushed to the repository:

1. GitHub automatically triggers the workflow
2. A virtual Ubuntu runner is created
3. The repository is checked out
4. Workflow steps are executed
5. Build completes successfully ✔️

---

## 🧰 Technologies Used

- GitHub Actions
- YAML
- HTML
- Git & GitHub
- Ubuntu (runner environment)

---

## 📁 Project Structure

```
github-actions-demo/
│
├── index.html
│
└── .github/
    └── workflows/
        └── main.yml
```

---

## ⚡ GitHub Actions Workflow

```yaml
name: CI Pipeline

on:
  push:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout repository
        uses: actions/checkout@v4

      - name: Run build step
        run: echo "GitHub Actions CI/CD pipeline executed successfully!"
```

---

## 🎯 Key Learnings

- CI/CD fundamentals
- GitHub Actions automation
- YAML workflow configuration
- Understanding DevOps pipelines
- Automation of build process on every push

---

## 📸 Status

✔ Workflow runs successfully  
✔ Build passes on every commit  
✔ CI pipeline fully automated  

---

## 👩‍💻 Author

Sadhana Mohan
