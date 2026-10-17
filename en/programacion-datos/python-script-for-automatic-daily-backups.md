---
title: "Python Script for Automatic Daily Backups"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0014"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Automation"
level: "intermediate"
description: "Generate a Python script that compresses a folder, saves dated backups, prunes old ones, and runs on a schedule."
tags: ["python", "automation", "backups", "scripts", "cron"]
variables: ["source folder", "backup destination", "operating system", "how many backups to keep"]
translation: "/es/programacion-datos/script-de-python-para-respaldos-automaticos-diarios"
---

Context: I want to back up the folder [source folder] to [backup destination] (an external drive, a network folder, or a cloud-synced folder) every day. I use [operating system] and want to keep [how many backups to keep].
Goal: Stop doing manual backups and always know whether the last one worked.
Deliverable: 1) A Python script that takes the source and destination as arguments, compresses the folder into a .zip or .tar.gz with the date in the filename, deletes the oldest backups based on how many to keep, and logs every run and every error. 2) How to schedule it to run daily on my operating system (cron, Task Scheduler, or launchd). 3) How to test it and how to restore a backup.
Criteria: Use only Python's standard library so it runs without installing anything. Handle common errors (missing folder, full disk, permissions) with clear messages, and verify the archive can be opened before deleting old backups, because a corrupt backup gives false security.
Format: The full script in one commented code block, followed by items 2 and 3 as a numbered list.
