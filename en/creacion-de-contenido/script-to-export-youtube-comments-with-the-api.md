---
title: "Script to Export YouTube Comments With the API"
model: "ChatGPT · Claude · Gemini"
image: "creacion-de-contenido.webp"
id: "CON-0058"
lang: en
type: text
category: "Content Creation: YouTube, Podcast & Blog"
category_slug: "creacion-de-contenido"
subcategory: "Automation"
level: "advanced"
description: "Get a commented script that pulls a video's comments through the YouTube API, handles errors, and saves them to CSV."
tags: ["youtube api", "programming", "comments", "javascript", "python"]
variables: ["programming language", "programming level"]
translation: "/es/creacion-de-contenido/script-para-exportar-comentarios-de-youtube-con-su-api"
---

Context: I want to analyze the comments on my YouTube videos. I'll be coding in [programming language] and my level is [programming level]. I already have, or can create, an API key in Google Cloud.
Goal: I need a script that downloads all top-level comments and their replies from a video and saves them to a CSV file for later analysis.
Deliverable: 1) The complete code using the YouTube Data API (comment threads endpoint) that takes a video ID or URL, walks through every page of results, and saves author, text, date, likes, and whether it's a reply. 2) Error handling for an invalid key, a missing video, disabled comments, exhausted quota, and network failures, with sensible retries. 3) Short instructions for storing the key securely (environment variable) and running the script. 4) A note on the quota cost per run.
Criteria: Readable code with comments explaining each block, because I'll be maintaining it. Use only official API features and follow its terms of service. If you have web search, check the current version of the API and the client library.
Format: One code block, followed by the instructions as a numbered list.
If any essential information is missing, ask me up to 3 questions before you start.
