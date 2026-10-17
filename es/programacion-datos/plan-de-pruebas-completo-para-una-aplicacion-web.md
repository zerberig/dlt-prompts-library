---
title: "Plan de pruebas completo para una aplicación web"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0062"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Calidad y seguridad"
level: "avanzado"
description: "Obtén estrategia de pruebas por niveles, escenarios para flujos críticos, herramientas, criterios y su integración en CI."
tags: ["plan de pruebas", "qa", "pruebas automatizadas", "rendimiento", "ci"]
variables: ["tu aplicación web", "flujos críticos", "situación actual de pruebas"]
translation: "/en/programacion-datos/complete-test-plan-for-a-web-application"
---

Contexto: Vamos a probar [tu aplicación web] (qué hace, stack y usuarios principales). Las funciones más críticas para el negocio son [flujos críticos]. Hoy contamos con [situación actual de pruebas] (por ejemplo: solo pruebas manuales, algunas pruebas unitarias, sin CI).
Objetivo: Un plan de pruebas que cubra funcionalidad, rendimiento y seguridad, priorizado según el riesgo y que el equipo pueda ejecutar.
Entregable: 1) Estrategia general basada en la pirámide de pruebas: qué cubrir con pruebas unitarias, de integración, de extremo a extremo, de rendimiento, de seguridad y de accesibilidad, y por qué. 2) Escenarios de prueba para cada flujo crítico, con casos negativos y de borde. 3) Herramientas sugeridas para cada tipo de prueba según mi stack. 4) Ambientes y datos de prueba necesarios. 5) Criterios de entrada y salida, y métricas de calidad. 6) Cómo integrarlo en el pipeline de CI.
Criterios: Prioriza por riesgo: más profundidad en lo que más daño causaría si falla. Define metas de rendimiento con valores concretos (por ejemplo, tiempo de respuesta en el percentil 95 con cierto número de usuarios concurrentes). Sé realista con el esfuerzo de mantener las pruebas de extremo a extremo.
Formato: Secciones numeradas; los escenarios en tabla con columnas ID, Flujo, Tipo de prueba, Pasos, Resultado esperado y Prioridad.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.
