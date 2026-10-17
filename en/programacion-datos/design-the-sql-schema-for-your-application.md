---
title: "Design the SQL Schema for Your Application"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0050"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "APIs and databases"
level: "advanced"
description: "Get an entity-relationship diagram, CREATE TABLE statements, indexes, sample queries, and seed data."
tags: ["sql", "data modeling", "database", "postgresql", "schema"]
variables: ["application description", "database engine", "entities and business rules", "expected data volume"]
translation: "/es/programacion-datos/disena-el-esquema-sql-de-tu-aplicacion"
---

Context: I'm building [application description] and will use [database engine] (for example: PostgreSQL, MySQL, SQLite). The main entities and their rules are: [entities and business rules]. I expect roughly [expected data volume].
Goal: A solid data model from day one, so I don't face painful migrations as the app grows.
Deliverable: 1) An entity-relationship diagram in Mermaid. 2) CREATE TABLE statements with data types, primary and foreign keys, NOT NULL, UNIQUE, and CHECK constraints, and defaults. 3) Recommended indexes based on the most frequent queries. 4) 5 sample queries for the main use cases. 5) Seed data with INSERT statements to validate the model.
Criteria: Normalize to third normal form and explain any intentional denormalization. Define what happens when related records are deleted (ON DELETE) according to the business rule. Include audit fields (created_at, updated_at) and consider soft deletes where it makes sense. Use consistent snake_case names and the exact syntax of the engine I specified.
Format: The diagram and each group of statements in separate code blocks, with a 1-to-2-line explanation per table.
If any essential information is missing, ask me up to 3 questions before you start.
