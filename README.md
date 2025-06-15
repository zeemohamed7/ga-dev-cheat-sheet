# 💻✨ Dev Cheat Sheet — Terminal • Git • VS Code

A quick reference guide for essential terminal commands, Git workflows, and VS Code shortcuts. Ideal for beginners and fast-paced development environments.

---

## 🖥️ Terminal Basics

```bash
📂 pwd              → Print working directory
* 📁 ls               → List files
* 🚪 cd <dir>         → Change directory
🏠 cd ~             → Home directory
⬆️  cd ..            → Move up one level
↩️  cd -             → Previous directory

❓ help / -h / --help / man   → Show help/manual
* 📄 touch <file>     → Create a file
📄 cat <file>       → Show file contents
* 📦 mkdir <dir>      → Create new directory
🖱️ open <file/dir>  → Open file/dir/URL in default app
👀 ps               → List running processes
🛑 kill <PID>       → Terminate a process by ID
🗑️ rm <file>        → Delete a file
🧹 rmdir <dir>      → Remove empty directory
```

---

## 🌱 Git Quick Start

```bash
📥 git clone <url>                   → Clone a repository
🌿 git checkout -b <branch>          → Create and switch to a new branch
🚀 git push -u origin <branch>       → Push new branch and track it
🔀 git checkout <branch>             → Switch to a branch
📤 git push origin <branch>          → Push existing branch
```

---

## 🧹 Git Cleanup

```bash
🗑️ git branch -d <branch>            → Delete local branch
🗑️ git push origin :<branch>         → Delete remote branch
```

---

## 🚧 Create a New Git Project

```bash
📁 cd project/
🧱 git init                          → Initialize a Git repo
➕ git add .                         → Stage all changes
✅ git commit -m "message"           → Commit with message
⛔ git rm --cached <file>           → Untrack file (e.g., missed .gitignore)
```

---

## 🌳 Branching & Merging

```bash
🌿 git branch                       → List all branches
🌱 git checkout -b <branch>         → Create and switch branch
✍️ git commit -a                    → Commit changes to tracked files
🔙 git checkout main                → Switch to main
🔗 git merge <branch>               → Merge branch into current
✏️ git branch -m <old> <new>        → Rename a branch
```

---

## 🧠 VS Code Shortcuts (Mac / Windows)

```plaintext
🖥️  Open Terminal:        Ctrl + `         | Ctrl + `
🧵 Word Wrap:             Option + Z       | Alt + Z
💾 Save File:             Cmd + S          | Ctrl + S
📚 Toggle Sidebar:        Cmd + B          | Ctrl + B
🎛️ Command Palette:       Shift + Cmd + P  | Shift + Ctrl + P
```

---

🧾 Feel free to fork this repo, contribute more shortcuts, or customize it for your team!
