# Learning Journal Design Specification (LJDS)

# 1. Repository Design

### 1.1 Repository Purpose

To store my learning progress.

---

### 1.2 Repository Name

```
learning-journal
```

---

### 1.3 Repository Description

A personal learning journal documenting my Cloud Engineering and DevOps learning journey, lessons learned, mistakes, and technical insights.

---

### 1.4 Repository Visibility

Public.

---

# 2. Repository Structure

```
learning-journal/
├── README.md
├── templates/
│   └── learning-journal-entry-template.md
│   └── learning-journal-entry-example.md
├── 2026-07-28-starting-my-learning-journal.md
├── 2026-07-30-understanding-git-commits.md
└── ...
```

---

# 3. Repository Workflow

The Learning Journal follows a simple Git workflow to ensure all entries are version controlled and synchronized with the remote repository.

## 3.1 Daily Workflow

When starting a new journal entry:

```
git pull origin main
```

This ensures the local repository is up to date before making changes.

After creating or updating a journal entry:

```
git status
git add .
git commit -m "Add learning journal entry: <entry-title>"
git push origin main
```

Replace `<entry-title>` with a short description of the journal entry.

Example:

```
git commit -m "Add learning journal entry: understanding git commits"
```

---

## 3.2 Commit Message Conventions

Commit messages should clearly describe the change being made.

### Adding a New Journal Entry

```
Add learning journal entry: <entry-title>
```

Example:

```
Add learning journal entry: linux file permissions
```

### Updating an Existing Journal Entry

```
Update learning journal entry: <entry-title>
```

Example:

```
Update learning journal entry: understanding docker images
```

### Updating the Journal Template

```
Update journal entry template
```

### Updating the README

```
Update learning journal README
```

### Updating Repository Documentation

```
Update learning journal documentation
```

---

# 4. Journal Entry Naming Convention

```
YYYY-MM-DD-short-descriptive-title.md
```

Examples:

```
2026-07-28-starting-my-learning-journal.md
2026-08-02-my-first-merge-conflict.md
2026-09-10-understanding-docker-images.md
```

---

# 5. Writing Guidelines

---

- One journal entry per Markdown file.
- Every entry uses the official template.
- Entries are organized chronologically by filename.
- Write in your own words.
- Keep entries concise.
- Focus on meaningful learning experiences rather than daily activity.
- Record lessons, not lectures.
- Avoid copying documentation.
- Prefer practical examples.

---

---

# 6. When to Write an Entry

- Important concept learned
- Mistake made
- Problem solved
- Milestone reached
- Insight gained

---

# 6. Workflow

Define the routine.

Example:

```
   Learn something
          ↓
        Reflect
          ↓
Create a new journal entry
          ↓
        Review
          ↓
        Commit
          ↓
    Push to GitHub
```

---
