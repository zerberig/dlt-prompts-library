---
title: "Design a REST API With Endpoints, Errors, and Auth"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0054"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "APIs and databases"
level: "advanced"
description: "Get an endpoint table, JSON schemas, consistent error handling, auth, pagination, and an OpenAPI snippet."
tags: ["rest api", "openapi", "api design", "backend", "authentication"]
variables: ["your product or system", "main resources", "who will consume the API", "language and framework"]
translation: "/es/programacion-datos/disena-una-api-rest-con-endpoints-errores-y-autenticacion"
---

Context: I need the API for [your product or system], which will handle these resources: [main resources] (for example: users, orders, products). It will be consumed by [who will consume the API], and we'll build it with [language and framework].
Goal: A consistent, easy-to-consume design the team can implement and document without ambiguity.
Deliverable: 1) An endpoint table. 2) Request and response JSON schemas for each resource, with types and validations. 3) An error strategy with a uniform format (for example, RFC 9457 Problem Details) and the HTTP status codes each endpoint will use. 4) Recommended authentication and authorization, with the reasoning. 5) Pagination, filtering, sorting, versioning, and idempotency for sensitive operations. 6) An OpenAPI 3.1 snippet covering 2 sample endpoints.
Criteria: Apply REST conventions consistently (plural nouns, HTTP methods used for their semantics, correct status codes). Think about the API consumer: useful error messages and predictable responses. Point out where more than one reasonable option exists and why you picked one.
Format: An endpoint table with the columns Method, Path, Description, Auth, and Responses; schemas and OpenAPI in code blocks.
If any essential information is missing, ask me up to 3 questions before you start.
