---
title: "Plan for a Predictive Maintenance Model"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0019"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Data science"
level: "advanced"
description: "Design, step by step, a model that predicts equipment failures from sensor data, from raw data to deployment."
tags: ["predictive maintenance", "machine learning", "sensors", "data science", "manufacturing"]
variables: ["type of equipment", "available sensor data", "failure history", "team tools"]
translation: "/es/programacion-datos/plan-para-un-modelo-de-mantenimiento-predictivo"
---

Context: We want to predict failures in [type of equipment] before they happen. Available sensor data: [available sensor data] (for example, temperature, vibration, pressure, or current, and the sampling rate). Failure and maintenance history: [failure history]. Team tools: [team tools].
Goal: A realistic project plan to go from raw data to alerts the maintenance team can actually use.
Deliverable:
1. Problem definition: what to predict (failure within the next N hours, remaining useful life, or anomaly) and why, given my data.
2. Data preparation: cleaning, syncing sensors, handling missing values, and how to label failures.
3. Feature engineering: time windows, rolling statistics, trends, and domain features.
4. Candidate models, from a simple baseline to more complex models, and when each one makes sense.
5. Validation: time-based data splits, metrics (recall, precision, lead time), and the cost of false alarms versus missed failures.
6. Deployment: how alerts reach the maintenance team, model monitoring, and retraining.
7. Risks, and what to do if few failures have been recorded.
Criteria: Start with the simplest thing that could work, because in maintenance the technicians' trust matters as much as accuracy. Avoid leaking future information into validation.
Format: Numbered sections with bullets and a short Python code example for feature engineering.
If any essential information is missing, ask me up to 3 questions before you start.
