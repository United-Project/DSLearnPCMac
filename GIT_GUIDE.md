# 🔁 Git Sync Guide: Seamless Workflow Between Mac & Windows

Keep your Jupyter notebooks, Python code, and notes in perfect sync across devices using Git + GitHub.

---

## ✅ Before You Start Editing (On Either Device)

```bash
git pull
```

> Downloads the latest changes from GitHub.

---

## 📝 After You Finish Editing

1. Save all files
2. Run the following commands in the VS Code terminal:

```bash
git add .
git commit -m "your message here"
git push
```

> Uploads your changes to GitHub, making them available for the other device.

---

## 🔁 Typical Workflow

### On Windows:

```bash
git pull
# Edit notebooks, scripts, notes
git add .
git commit -m "Updated from Windows"
git push
```

### On Mac:

```bash
git pull
# Edit notebooks, scripts, notes
git add .
git commit -m "Updated from Mac"
git push
```

---

## ✅ Visual Git Option

If you prefer not to use terminal:

- Use the **Source Control panel** in VS Code
  - Click the ↓ button to Pull
  - Click + to Stage
  - Type a commit message
  - Click the ↑ button to Push

Or use [GitHub Desktop](https://desktop.github.com/)

---

## 🧠 Pro Tips

- Run `git status` anytime to check what's changed
- Never edit the same notebook on both devices _without pushing/pulling first_
- You can open this `.md` file anytime for a refresher

---

## 💾 Stored in: `GIT_GUIDE.md`

Keep this in the root of your project for reference
