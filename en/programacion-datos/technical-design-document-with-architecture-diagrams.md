---
title: "Technical Design Document With Architecture Diagrams"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0025"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Architecture"
level: "advanced"
description: "Write a technical design doc with components, data flow, Mermaid diagrams, and an implementation plan."
tags: ["design document", "diagrams", "mermaid", "architecture", "technical documentation"]
variables: ["your product or feature", "main use case", "technologies", "requirements and constraints"]
translation: "/es/programacion-datos/documento-de-diseno-tecnico-con-diagramas-de-arquitectura"
---

Context: I need the technical design document for [your product or feature], which solves [main use case]. Technologies: [technologies]. Requirements and constraints: [requirements and constraints].
Goal: A document the team can review before coding that also serves as a reference for whoever joins later.
Deliverable:
1. Summary, goals, and what's out of scope.
2. A context diagram and a container or component diagram in Mermaid.
3. A description of each component: responsibility, interfaces, and technology.
4. Data flow for the main use case with a Mermaid sequence diagram.
5. Data model and main API contracts.
6. Security, observability, and error handling.
7. Alternatives considered and why they were rejected.
8. A phased implementation plan and open questions.
Criteria: Write for a developer who wasn't in the earlier conversations: clear, specific, and without filler. Every diagram must be valid Mermaid code that can be pasted and rendered.
Format: A Markdown document with a heading per section and diagrams in mermaid code blocks.
If any essential information is missing, ask me up to 3 questions before you start.
