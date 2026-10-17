---
title: "Pruebas unitarias listas para correr para tu código"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0018"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Testing y QA"
level: "intermedio"
description: "Genera pruebas unitarias que cubren camino feliz, casos límite y errores de tu función o módulo, con Pytest, Jest u otro."
tags: ["pruebas unitarias", "pytest", "jest", "testing", "cobertura"]
variables: ["lenguaje y framework de pruebas", "comportamiento esperado", "tu código"]
translation: "/en/programacion-datos/ready-to-run-unit-tests-for-your-code"
---

Contexto: Necesito pruebas unitarias en [lenguaje y framework de pruebas] (por ejemplo, Python con Pytest o JavaScript con Jest) para esta función o módulo. Comportamiento esperado: [comportamiento esperado].
[tu código]
Objetivo: Poder refactorizar con confianza y detectar regresiones en CI.
Entregable: 1) Lista breve de los escenarios que vas a cubrir: camino feliz, casos límite (vacíos, nulos, extremos, tipos inesperados), errores y excepciones. 2) El archivo de pruebas completo, listo para correr. 3) Qué dependencias simulaste con mocks y por qué. 4) Comportamientos ambiguos o posibles errores del código que detectes al escribir las pruebas.
Criterios: Nombres de prueba que describan el comportamiento, una aserción principal por prueba y pruebas independientes entre sí, porque así un fallo dice exactamente qué se rompió. Usa parametrización para casos similares. Si el código tiene un error, no ajustes la prueba para que pase: señálalo.
Formato: La lista de escenarios, luego el archivo de pruebas en un bloque de código y al final las notas.
