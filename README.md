# 📘 Personal English Learning System

**Welcome to my personalized English learning system — driven by real mistakes and reinforced with AI.**

This repository documents my journey to mastering English, step by step, by capturing real usage, analyzing errors, and correcting them through intentional practice.

---

## 🎯 Purpose

This project is designed to:

- Capture spontaneous English (spoken or written)
- Identify actual errors in grammar, vocabulary, pronunciation, or fluency
- Practice those mistakes repeatedly through interactive exercises
- Track progress over time with status updates
- Use AI (like ChatGPT) to guide correction, practice, and evaluation

---

## 📁 Structure

| File / Folder                        | Description                                                           |
|-------------------------------------|------------------------------------------------------------------------|
| `miguel-en-errors.json`             | The main file. A growing database of my personal English mistakes.     |
| `miguel-en-errors.backup.2024-06-19.json` | Backup copy of the database as of June 19, 2024.                 |
| `/prompts/`                         | AI prompt templates for each stage of the learning process             |
| `README.md`                         | Project documentation and system overview.                             |
| *(coming soon)* `/scripts/`         | For Python or JS tools that help manage or test the data.              |


---

## 🔗 Accessing the JSON Error Log

You can access the live error log directly using the raw GitHub URL below.  
This URL is useful for AI prompts, scripts, or tools that need to read the personalized mistake data in real-time:
https://raw.githubusercontent.com/Miguelepst/personal-englsih-system/main/miguel-en-errors.json

> 💡 This is the recommended format for accessing raw files in GitHub.  
It avoids longer versions like `/refs/heads/` and works better with external systems.

If you're using this link in a script or AI assistant, just make sure your tool can read `.json` from a public URL.
---

## 🧩 System Stages

The system is structured in **five progressive stages**:

### 1. 🟢 Spontaneous Capture
I speak or write in English naturally. AI records exactly what I say — with **no correction** — to preserve authentic usage.

### 2. 🟡 Error Analysis
AI detects errors and generates structured entries with:
- Mistake type
- Suggested correction
- Explanation
- Status (`"Nuevo"`, `"En práctica"`, `"Corregido"`)

These entries are stored in `errors.json`.

### 3. 🔵 Intensive Practice (Game Mode)
I work on my actual mistakes through a fun, interactive game-style prompt based on my `errors.json` log.

### 4. 🟣 Error Management
This stage tracks what’s been practiced and updates the status of each error. This avoids repeating the same errors too often and ensures all are covered over time.

### 5. 🔴 Certification & Evaluation
In this final stage, AI challenges me to prove I’ve mastered specific errors. Only after successfully passing is an error marked `"Corregido"`.

---

## 🧠 Philosophy

This project is built on one core idea:  
> “Don’t just learn English — learn **your** English.”

By focusing on **real, personal mistakes**, learning becomes more effective, relevant, and motivating.

---

## 🚀 Future Vision

This repository may evolve to include:

- Tools in Python/JavaScript for data handling
- Visual dashboards for tracking progress
- Speech-to-text support
- Reports and export features
- Templates for other learners to replicate this model

---

## 🤝 Contributions

This is a personal project, but feel free to fork or adapt it for your own learning.

If you’re an educator, language learner, or developer interested in collaboration, feel free to open an issue or get in touch.

---

## 📬 Maintainer & Contact

This project is maintained by **Miguel Gutiérrez** as part of a personal and strategic mission to improve English fluency through real-world usage, AI feedback, and intentional practice.

If you'd like to:

- Ask questions about the system
- Share feedback or ideas
- Collaborate on tools, prompts, or methodology
- Adapt this system for your own learning

Feel free to open an issue on the GitHub repository  
or contact me directly: **[your_email_here]** (optional)


---

## 🧰 Backup Management

To understand how and when to create backups of your error log, please refer to the [📄 Backup Guide](./BACKUP_GUIDE.md).

This guide includes:

- 📦 Naming conventions
- 🔁 When to create backups
- 🛠 How to restore a backup safely
- 💡 Best practices to keep your data safe

Keeping regular backups ensures you never lose your learning progress.


📘 Want to learn more about how the system works in detail?  
Check the full methodology here → [/docs/full-methodology.md](./docs/full-methodology.md)


