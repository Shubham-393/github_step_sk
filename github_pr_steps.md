# 🚀 GitHub Group Project – Internship Workflow

A step-by-step guide to collaborate on a group project by **forking a friend's repo** and making your contributions effectively using Git and GitHub.

---

## 📌 Commands Reference Table

| Task                              | Command/Instruction                                         |
|-----------------------------------|-------------------------------------------------------------|
| Fork repo                         | Use GitHub UI – Click **Fork**                              |
| Clone your fork                   | `git clone <your-fork-url>`                                 |
| Add upstream                      | `git remote add upstream <friend's repo>`                   |
| Create new branch                 | `git checkout -b branch-name`                               |
| Pull latest from upstream         | `git pull upstream main`                                    |
| Commit changes                    | `git add .` <br> `git commit -m "your message"`             |
| Push changes                      | `git push origin branch-name`                               |
| Create pull request               | Use GitHub UI after pushing branch                          |

---

## ✅ 1. Fork the Friend’s Repository
- Visit your friend's GitHub repository.
- Click the **"Fork"** button (top-right corner).
- This creates a copy under your GitHub account.

---

## ✅ 2. Clone Your Forked Repository
```bash
git clone https://github.com/your-username/project-name.git
cd project-name
```

---

## ✅ 3. Add the Original Repository as a Remote
```bash
git remote add upstream https://github.com/friend-username/project-name.git
```

You now have:
- `origin` → your fork
- `upstream` → original (friend’s) repo

---

## ✅ 4. Create a New Branch for Your Work
```bash
git checkout -b your-feature-branch-name
```

Example:
```bash
git checkout -b add-feedback-graph
```

---

## ✅ 5. Do Your Work (Code / Fix / Add)
- Make necessary changes.
- Save files and commit:
```bash
git add .
git commit -m "Add: Feedback graph on results page"
```

---

## ✅ 6. Pull Latest Changes from Original Repo (Upstream)
To keep your local and fork updated:
```bash
git checkout main
git pull upstream main
git checkout your-feature-branch-name
git merge main
```

---

## ✅ 7. Push Your Branch to Your Forked Repo
```bash
git push origin your-feature-branch-name
```

---

## ✅ 8. Create a Pull Request (PR)
- Go to your fork on GitHub.
- Click **"Compare & pull request"**.
- Write a **clear PR title** and **description**.
- Assign reviewers (if any).

---

## ✅ 9. Repeat for Every New Contribution
Each time:
- Pull latest upstream changes.
- Create a **new branch**.
- Make your changes.
- Push and create a new PR.

---

## 🧠 Team Collaboration Tips
- Use a shared group chat (WhatsApp/Slack/Discord).
- Track tasks using GitHub **Issues** or a Kanban board (Projects tab).
- Use consistent commit messages:
  - `feat: add AI answer evaluation module`
  - `fix: corrected marks calculation bug`

---


## 📁 Optional Files for Better Collaboration
- `README.md` → Project overview
- `CONTRIBUTING.md` → Guidelines to contribute
- `.gitignore` → Ignore unnecessary files
- `requirements.txt` or `environment.yml` → Dependencies

---

Happy coding! 🎯
