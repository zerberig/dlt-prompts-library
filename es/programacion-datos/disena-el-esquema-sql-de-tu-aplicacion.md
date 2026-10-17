---
title: "Diseña el esquema SQL de tu aplicación"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0050"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "APIs y bases de datos"
level: "avanzado"
description: "Obtén diagrama entidad-relación, sentencias CREATE TABLE, índices, consultas de ejemplo y datos de prueba."
tags: ["sql", "modelado de datos", "base de datos", "postgresql", "esquema"]
variables: ["descripción de la aplicación", "motor de base de datos", "entidades y reglas de negocio", "volumen de datos esperado"]
translation: "/en/programacion-datos/design-the-sql-schema-for-your-application"
---

Contexto: Estoy construyendo [descripción de la aplicación] y usaré [motor de base de datos] (por ejemplo: PostgreSQL, MySQL, SQLite). Las entidades principales y sus reglas son: [entidades y reglas de negocio]. Espero un volumen aproximado de [volumen de datos esperado].
Objetivo: Un modelo de datos sólido desde el inicio, para no tener que hacer migraciones dolorosas cuando la app crezca.
Entregable: 1) Diagrama entidad-relación en Mermaid. 2) Sentencias CREATE TABLE con tipos de datos, llaves primarias y foráneas, restricciones NOT NULL, UNIQUE y CHECK, y valores por defecto. 3) Índices recomendados según las consultas más frecuentes. 4) 5 consultas de ejemplo para los casos de uso principales. 5) Datos de prueba con INSERT para validar el modelo.
Criterios: Normaliza hasta tercera forma normal y explica cualquier desnormalización intencional. Define qué pasa al borrar registros relacionados (ON DELETE) según la regla de negocio. Incluye campos de auditoría (created_at, updated_at) y considera el borrado lógico donde tenga sentido. Usa nombres consistentes en snake_case y la sintaxis exacta del motor que indiqué.
Formato: El diagrama y cada grupo de sentencias en bloques de código separados, con una explicación de 1 o 2 líneas por tabla.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.
