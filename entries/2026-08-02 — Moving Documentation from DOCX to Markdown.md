# 2026-08-02 — Moving Documentation from DOCX to Markdown

> **Related Topic(s):** Git, GitHub, Linux

---

## What Happened

I decided to shift my primary documentation and note-taking format from Microsoft Word (`.docx`) to Markdown (`.md`). 

I liked how things are simply organized and structured inside Markdown documents. I found it easier to create and have templates via Markdown than Microsoft Word.

Markdown is plain-text which allows me to read, edit, search, and process documentation directly through the Command Line Interface using standard tools like `cat`, `grep`, `less`, or `kate`.

Additionally, standard `.docx` files are binary, making them incompatible with line-by-line version control.

Moving to Markdown enables clean `git diff` tracking, easier commit histories, and native rendering inside GitHub repositories (GitHub understands their format and shows them easily).

---

## Lessons Learned

- Plain-text formats integrate seamlessly with CMD.
- Binary formats (`.docx`) hinder Git's version control capabilities like detailed diffs and code reviews.
- Writing in Markdown eliminates formatting distractions and speeds up technical note-taking.

---
