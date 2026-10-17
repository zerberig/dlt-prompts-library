---
title: "Plan de pruebas completo para una nueva funcionalidad"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0001"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Testing y QA"
level: "avanzado"
description: "Obtén un plan de pruebas con alcance, estrategia, casos clave, entornos, riesgos y criterios de salida para tu release."
tags: ["plan de pruebas", "qa", "testing", "casos de prueba", "release"]
variables: ["funcionalidad", "tu producto", "descripción técnica y requisitos", "fecha de lanzamiento y equipo"]
translation: "/en/programacion-datos/complete-test-plan-for-a-new-feature"
---

Contexto: Vamos a lanzar [funcionalidad] en [tu producto]. Esto es lo que hace y cómo está construida: [descripción técnica y requisitos]. Restricciones de calendario y equipo: [fecha de lanzamiento y equipo].
Objetivo: Quiero un plan de pruebas que el equipo pueda seguir para decidir con datos si la funcionalidad está lista para producción.
Entregable:
1. Alcance: qué se prueba y qué queda fuera, con el motivo.
2. Estrategia: tipos de prueba (unitarias, integración, extremo a extremo, rendimiento, seguridad, accesibilidad) y cuáles automatizar.
3. Entre 15 y 25 casos de prueba clave, incluidos escenarios de error y casos límite.
4. Entornos y datos de prueba necesarios.
5. Riesgos y escenarios de falla más probables, con cómo detectarlos.
6. Criterios de entrada y salida, y métricas para medir la calidad del release.
Criterios: Prioriza por riesgo para el usuario y para el negocio, porque el tiempo de pruebas es limitado. Cada caso debe poder ejecutarlo alguien que no escribió el código.
Formato: Secciones numeradas; los casos en una tabla con las columnas ID, Escenario, Pasos, Datos, Resultado esperado y Prioridad.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.
