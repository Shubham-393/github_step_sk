# 🧑‍💻 Collaborative GitHub Workflow (As a Collaborator)

### ✅ 1. **Accept the Invitation**

- Go to your email or GitHub notifications.
- Accept the invite to become a collaborator on the repository.

---

### ✅ 2. **Clone the Repository**

Open your terminal and run:

```bash
git clone https://github.com/username/repo-name.git
cd repo-name
```

> Replace `username` and `repo-name` with the actual details.

---

### ✅ 3. **Set Up Git Config (If Not Done Already)**

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

---

### ✅ 4. **Pull Latest Changes Before Starting Work**

To make sure you're working on the most recent version of the code:

```bash
git checkout main
git pull origin main
```

> Do this **before creating a new branch**, especially if others may have pushed changes.

---

### ✅ 5. **Create a New Branch for Your Work**

This helps keep the main branch clean:

```bash
git checkout -b your-feature-branch
```

---

### ✅ 6. **Make Changes and Commit**

Edit files as needed, then:

```bash
git add .
git commit -m "Describe your changes"
```

---

### ✅ 7. **Push Your Branch**

```bash
git push origin your-feature-branch
```

---

### ✅ 8. **Create a Pull Request**

Go to the GitHub repo page and:

- Click **"Compare & pull request"**
- Add a description
- Submit the PR for review

---

### ✅ 9. **Review and Collaborate**

- Discuss changes via PR comments
- Make updates as requested
- Once approved, the changes can be merged into the main branch

---

> 💡 **Tip:** Regularly run `git pull origin main` on your local `main` branch to stay in sync with teammates.

Would you like help setting up a GitHub Project board or an issue-tracking workflow?
