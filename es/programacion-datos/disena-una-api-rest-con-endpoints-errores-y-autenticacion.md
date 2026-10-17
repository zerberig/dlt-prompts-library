---
title: "Diseña una API REST con endpoints, errores y autenticación"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0054"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "APIs y bases de datos"
level: "avanzado"
description: "Obtén tabla de endpoints, esquemas JSON, manejo de errores uniforme, autenticación, paginación y un fragmento OpenAPI."
tags: ["api rest", "openapi", "diseño de apis", "backend", "autenticación"]
variables: ["tu producto o sistema", "recursos principales", "quién consumirá la API", "lenguaje y framework"]
translation: "/en/programacion-datos/design-a-rest-api-with-endpoints-errors-and-auth"
---

Contexto: Necesito la API de [tu producto o sistema], que manejará estos recursos: [recursos principales] (por ejemplo: usuarios, pedidos, productos). La consumirán [quién consumirá la API] y la implementaremos con [lenguaje y framework].
Objetivo: Un diseño consistente y fácil de consumir que el equipo pueda implementar y documentar sin ambigüedades.
Entregable: 1) Tabla de endpoints. 2) Esquemas de solicitud y respuesta en JSON para cada recurso, con tipos y validaciones. 3) Estrategia de errores con formato uniforme (por ejemplo, Problem Details del RFC 9457) y los códigos HTTP que usará cada endpoint. 4) Autenticación y autorización recomendadas, con su razón. 5) Paginación, filtrado, ordenamiento, versionado e idempotencia para operaciones sensibles. 6) Un fragmento de especificación OpenAPI 3.1 con 2 endpoints de ejemplo.
Criterios: Sigue las convenciones REST de forma consistente (sustantivos en plural, métodos HTTP según su semántica, códigos de estado correctos). Piensa en quien consume la API: mensajes de error útiles y respuestas predecibles. Señala los puntos donde haya más de una opción razonable y por qué elegiste una.
Formato: Tabla de endpoints con columnas Método, Ruta, Descripción, Autenticación y Respuestas; esquemas y OpenAPI en bloques de código.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.
