# 🧭 Galhoom Path — Study Template (Global Blueprint)

> 🛤️ **Part of [Galhoom Path](https://github.com/galhoom-path)** · Track 1 — Study (**global blueprint**)  
> This repository belongs to the **Galhoom Path** organization. It is the shared template for every Study-track repo.  
> → [Organization home](https://github.com/galhoom-path)

This repository holds the **shared blueprint** used by every study repo in [galhoom-path](https://github.com/galhoom-path).

**One file drives the method:**

📄 [`template.md`](./template.md)

It defines Lectures → Interview Questions → Final Project, naming rules, tutor/student roles, living-repo updates, series-without-overlap, and the AI prompt to generate a new subject repo.

---

## 🎯 Why this repo exists

| Without a global template | With this repo |
|:---|:---|
| Each study repo drifts into its own rules | One official method for PHP, OOP, OOD, Laravel, … |
| Hard to remember which copy is newest | **This repo is the source of truth** |
| New subjects start from memory | New subjects start by copying `template.md` |

---

## 🔄 Sync rule (mandatory)

```
Improve the method in any study repo
        │
        ▼
1. Update template.md HERE first (study-template)
        │
        ▼
2. Copy the same change into every active study repo's template.md
   (and .cursor/rules/template-sync.mdc when Section 18 changes)
        │
        ▼
3. Bump "Template last synced" date in this file to today
```

**Never** leave a study repo’s `template.md` newer than this one without pushing the change back here.

When you only change **subject content** (lectures, questions, project) — do **not** touch this repo.

When you change **structure, conventions, or method** — update this repo in the same change.

---

## 🚀 How to create a new study repo

1. Create an empty public repo under `galhoom-path` (for example `php-ood`).
2. Copy [`template.md`](./template.md) into the new repo root.
3. Copy `.cursor/rules/template-sync.mdc` from Section 18 of `template.md` (or from an existing study repo).
4. Fill the placeholders in Section 2 of `template.md` for the new subject.
5. Paste the AI prompt from Section 17 into a new chat, attach `template.md`, and generate the scaffold.
6. Add the new repo to the Learning Series table on the [org homepage](https://github.com/galhoom-path).
7. Link **Comes after** / **Leads to** to the neighboring repos — no repeated lessons.

---

## 📦 Study repos that use this template

| Repo | Role |
|:---|:---|
| [php-fundamentals](https://github.com/galhoom-path/php-fundamentals) | Series 1 — core PHP |
| [php-oop](https://github.com/galhoom-path/php-oop) | Series 2 — OOP |
| `php-ood` | Series 3 — planned |

Each of those keeps its **own copy** of `template.md` so the repo stays self-contained for learners and AI tutors. This repo is where the **shared method** is maintained.

---

## 📁 What’s in this repository

```
study-template/
├── README.md      ← you are here
└── template.md    ← the global Galhoom Study Method blueprint
```

No lecture folders. No student practice files. Method only.

---

## 🛠️ Maintainer

[@Galhoom22](https://github.com/Galhoom22) · Organization: [galhoom-path](https://github.com/galhoom-path)

**📘 Read. ✍️ Write. 💬 Explain. 🏗️ Build. 🏅 Master.**
