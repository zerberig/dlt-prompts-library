---
title: "Spec an Economic Indicators Dashboard"
model: "ChatGPT · Claude · Gemini"
image: "finanzas-contabilidad.webp"
id: "FIN-0019"
lang: en
type: text
category: "Finance & Accounting"
category_slug: "finanzas-contabilidad"
subcategory: "Fintech product"
level: "advanced"
description: "Design an economic indicators dashboard with official sources, charts, alerts, and refresh frequency."
tags: ["economic indicators", "dashboard", "data visualization", "macroeconomics", "product spec"]
variables: ["country or region", "dashboard users", "decisions the dashboard will support"]
translation: "/es/finanzas-contabilidad/especificacion-de-un-tablero-de-indicadores-economicos"
---

Context: I want to build an economic indicators dashboard for [country or region] for [dashboard users] (investors, company leadership, analysts, etc.). They'll use it for [decisions the dashboard will support].
Goal: Users should understand how the economy is doing and what changed since their last check in under a minute, without getting lost in data.
Deliverable: 1) The 10 most useful indicators for this audience (for example, inflation, policy interest rate, exchange rate, unemployment, GDP, consumer confidence): for each, what it measures, why it matters for those decisions, release frequency, and official source. 2) The best visualization for each indicator and the time range to show. 3) The main view layout: hierarchy, filters, and comparisons. 4) Alert rules (thresholds or meaningful changes). 5) Data requirements: refresh schedule, handling of revisions, and methodology notes.
Criteria: If you have web search, confirm the current official sources (central bank, statistics office) and their release calendars. Favor clarity over quantity: each chart should answer one specific question. Flag which data is preliminary and gets revised later.
Format: An indicator table with the columns Indicator, What it measures, Why it matters, Frequency, Source, and Visualization; then sections for the main view, alerts, and data requirements.
