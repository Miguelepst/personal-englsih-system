### 📁 `/SYSTEM_OVERVIEW.md` or `/full-methodology.md` 

✅ Personal English Learning System – Full Overview

This document summarizes the complete structure and methodology of the personalized English learning system developed by Miguel Gutiérrez. The system is powered by real personal mistakes and AI-guided correction and practice.


---

🔢 System Stages (Prompts)

1. 🟢 Stage 1 – Spontaneous Capture ("Captura espontánea")

You speak or write in English naturally.

AI only transcribes what you say — including pauses, errors, or mixed Spanish.

No correction is made at this point.


2. 🟡 Stage 2 – Error Analysis & JSON Registration

AI analyzes your spontaneous content.

All errors are identified and categorized:

Grammar

Vocabulary

Fluency

Pronunciation

Spanish usage


For each error, a structured block is created in .json format, including:

id, fecha, frase_original, correccion_sugerida, tipo_error, comentario, estado


File updated: miguel-en-errors.json


3. 🔵 Stage 3 – Intensive Practice (Game Mode)

Interactive game: "How do you say it in English?"

Uses miguel-en-errors.json to select real mistakes and correct them interactively.

You repeat, choose, listen, and practice the correct forms.

Game loop includes speaking practice and repetition.


4. 🟣 Stage 4 – Error Log Management

Tracks which errors are already being worked on.

Automatically changes error status:

From "Nuevo" → "En práctica"

From "En práctica" → "Corregido"


Ensures full coverage of all errors over time.


5. 🔴 Stage 5 – Certification & Evaluation

Conducts intelligent tests to confirm whether an error is truly corrected.

Can include traps or variations to ensure mastery.

Only certified errors are marked as "Corregido".

Adds rigor and closure to the process.



---

📁 Repository Structure

File / Folder	Description

miguel-en-errors.json	The main database of personal English mistakes
miguel-en-errors.backup.2024-06-19.json	A backup copy as of June 19, 2024
/prompts/	AI prompt templates for each stage of the learning process
README.md	Main documentation and project overview
(coming soon) /scripts/	Python/JS tools for managing or testing the data



---

🔗 Access to the Error Log

Raw GitHub URL to access the JSON file directly:

https://raw.githubusercontent.com/Miguelepst/personal-englsih-system/main/miguel-en-errors.json

This is used by scripts or AI prompts.

Recommended format: raw access (avoids /refs/heads/... style).



---

📦 Backups

Backups use the format: miguel-en-errors.backup.YYYY-MM-DD.json

Best practice: create a backup after every major session.

Backups are listed in the README.md under the repository structure section.



---

🧠 Philosophy

> "Don’t just learn English — learn your English."



You don’t study generic content.

You fix your own real errors, making learning efficient, targeted, and meaningful.



---

🚀 Future Vision

Python/JS tools for error tracking

Speech-to-text integrations

Visual dashboards

Progress reports

Templates for other learners



---

📬 Maintainer

This system is maintained by Miguel Gutiérrez, as part of a personal mission to improve English fluency using real mistakes and AI.

Feel free to fork this idea or open an issue if you’d like to collaborate or adapt the methodology.

