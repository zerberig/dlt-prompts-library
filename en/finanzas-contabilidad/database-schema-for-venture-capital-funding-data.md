---
title: "Database Schema for Venture Capital Funding Data"
model: "ChatGPT · Claude · Gemini"
image: "finanzas-contabilidad.webp"
id: "FIN-0036"
lang: en
type: text
category: "Finance & Accounting"
category_slug: "finanzas-contabilidad"
subcategory: "Fintech product"
level: "advanced"
description: "Design the database schema for a venture capital platform: tables, relationships, indexes, and SQL."
tags: ["database", "venture capital", "sql", "data modeling", "startups"]
variables: ["platform scope", "database engine", "most common queries"]
translation: "/es/finanzas-contabilidad/esquema-de-base-de-datos-para-capital-de-riesgo"
---

Context: We're building a platform to search and analyze data on [platform scope] (startups, funding rounds, funds, and investors, for example in a given country or region). We'll use [database engine], and the most common queries will be: [most common queries].
Goal: I want a schema that keeps data consistent, supports those queries with good performance, and can grow without a redesign.
Deliverable: 1) An entity-relationship diagram described in text: entities (companies, rounds, investors, round participations, people, sectors, locations, data sources) and their relationships. 2) For each table: fields, data types, primary and foreign keys, constraints, and required fields. 3) The SQL script to create the tables. 4) Recommended indexes for the common queries, with the reasoning. 5) How to handle amounts in different currencies, unconfirmed valuations, company name changes, and change history. 6) Three sample SQL queries.
Criteria: Normalize as far as it makes sense and explain any denormalization. Include a source and verification-date field on each record, because provenance matters in investment data. Use English snake_case names for tables and fields.
Format: Sections with headings, one table per entity with the columns Field, Type, Constraints, and Description, and the SQL in code blocks.
If any essential information is missing, ask me up to 3 questions before you start.
