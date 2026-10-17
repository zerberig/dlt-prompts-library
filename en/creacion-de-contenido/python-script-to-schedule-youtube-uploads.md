---
title: "Python Script to Schedule YouTube Uploads"
model: "ChatGPT · Claude · Gemini"
image: "creacion-de-contenido.webp"
id: "CON-0017"
lang: en
type: text
category: "Content Creation: YouTube, Podcast & Blog"
category_slug: "creacion-de-contenido"
subcategory: "Automation"
level: "advanced"
description: "Get a Python script that uploads and schedules videos with titles, descriptions, and tags from a spreadsheet."
tags: ["python", "youtube api", "automation", "metadata"]
variables: ["channel topic", "spreadsheet format", "your programming level"]
translation: "/es/creacion-de-contenido/script-en-python-para-programar-subidas-a-youtube"
---

Context: I have finished videos for my channel about [channel topic] in a local folder, plus a spreadsheet in [spreadsheet format] (CSV or Google Sheets) with columns for file, title, description, tags, thumbnail, playlist, and publish date. My programming level is [your programming level].
Goal: Upload and schedule the videos in bulk with their metadata, instead of loading them one by one in YouTube Studio.
Deliverable: 1) A Python script that uses the YouTube Data API (v3) with OAuth authentication, uploads each video as private with a scheduled publish date, sets the thumbnail and playlist, and writes the result to a log file. 2) Setup instructions: Google Cloud project, credentials, dependencies, and how to run it. 3) A description template with a call to action and placeholders for links.
Criteria: Validate the spreadsheet data before uploading (file exists, title length, future date) and handle errors without stopping the whole batch. Explain the API's daily quota and how to avoid running out; if you have web search, confirm the current limits and flag anything that's an estimate. Keep credentials out of the code.
Format: Complete, commented code in one block, followed by the setup guide as numbered steps.
If any essential information is missing, ask me up to 3 questions before you start.
