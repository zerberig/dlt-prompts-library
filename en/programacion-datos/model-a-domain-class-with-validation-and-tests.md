---
title: "Model a Domain Class With Validation and Tests"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0067"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Fundamentals"
level: "intermediate"
description: "Practice object-oriented design with a class diagram, an encapsulated implementation, tests, and extensions."
tags: ["object-oriented programming", "classes", "unit tests", "software design", "coding practice"]
variables: ["language", "entity or system"]
translation: "/es/programacion-datos/modela-una-clase-de-dominio-con-validaciones-y-pruebas"
---

Context: I'm practicing object-oriented design in [language]. I want to model [entity or system] (for example: a bank account with deposits, withdrawals, and balance checks).
Goal: A reference implementation that shows good design practices, not just code that works.
Deliverable: 1) A Mermaid class diagram with attributes, methods, and relationships. 2) The complete implementation with encapsulation (private fields and validation inside methods) and error handling through exceptions or explicit results (for example: a withdrawal larger than the balance, or a negative amount). 3) A short sample program that uses the class. 4) Unit tests for normal and error cases. 5) 2 suggested extensions for further practice (for example: transaction history, account types using inheritance or composition).
Criteria: Use types that suit the domain (for money, a decimal type instead of floating point, because it avoids rounding errors). Idiomatic code for the language, with clear names and comments only where they add something. Briefly explain each design decision.
Format: Numbered sections, with the diagram, code, and tests in separate blocks.
