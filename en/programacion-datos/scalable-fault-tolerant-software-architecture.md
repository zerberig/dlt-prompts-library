---
title: "Scalable, Fault-Tolerant Software Architecture"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0005"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Architecture"
level: "advanced"
description: "Design an architecture with load estimates, scaling, caching, partitioning, and failure handling, with trade-offs."
tags: ["software architecture", "scalability", "high availability", "fault tolerance", "distributed systems"]
variables: ["your product", "expected load", "key requirements", "stack or constraints"]
translation: "/es/programacion-datos/arquitectura-escalable-y-tolerante-a-fallos"
---

Context: I'm designing the architecture for [your product]. Expected load today and in 2 years: [expected load]. Key requirements: [key requirements] (availability, latency, security, compliance). Stack or constraints: [stack or constraints].
Goal: An architecture that handles growth and keeps working when a piece fails, without overpaying for scale I don't need yet.
Deliverable:
1. A quick capacity estimate (requests per second, storage, bandwidth) with explicit assumptions.
2. Two architecture options, one simpler and one built for higher scale, with components and data flow.
3. Scalability decisions: load balancing, caching, data partitioning, queues, and async processing.
4. Failure analysis: what happens if each critical component goes down, how it's detected, and how it recovers.
5. A final recommendation and the point at which it would make sense to move to the next stage.
Criteria: Justify every decision with its trade-off (cost, complexity, consistency), because there's no right architecture without context. Flag any capacity or cost figure you can't back up as an estimate.
Format: Numbered sections, a comparison table of the two options, and a Mermaid diagram of the recommended option.
If any essential information is missing, ask me up to 3 questions before you start.
