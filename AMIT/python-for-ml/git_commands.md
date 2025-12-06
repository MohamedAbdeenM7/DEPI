# Git Commands

simple, clean list of the most common Git commands you will need in daily development.

## Basics

- **intialization a new repository**

```bash
git init repo
```

- **Check the status of files**

```bash
git status
```

- **Add a file or all files**

```bash
git add filename
git add .
```

- **Create a commit**

```bash
git commit -m "Commit message"
```

## 🔹 Working with Remote (GitHub)

- **Connect the local repo to GitHub**

```bash
git remote add origin <URL>
```

- **Push code to GitHub**

```bash
git push -u origin main
```

- **Pull the latest updates from GitHub**

```bash
git pull
```

## 🔹 Branches

- **Create a new branch**

```bash
git branch branch-name
```

- **Switch to a branch**

```bash
git checkout branch-name
```

- **Merge a branch into main**

```bash
git merge branch-name
```

## 🔹 Full Git Repository

- **Clone a repository**

```bash
git clone <URL>
```

## 🔹 Reset & Undo Changes

- **Discard changes in a file (before staging)**

```bash
git checkout -- filename
```

- **Remove a file from staging**

```bash
git reset filename
```

- **Reset to the most recent commit**

```bash
git reset --hard HEAD
```

## 🔹 Commit History

- **Show commit history**

```bash
git log
```
