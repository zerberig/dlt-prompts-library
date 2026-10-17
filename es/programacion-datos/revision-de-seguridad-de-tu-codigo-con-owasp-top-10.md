---
title: "Revisión de seguridad de tu código con OWASP Top 10"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0030"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Calidad y seguridad"
level: "avanzado"
description: "Detecta vulnerabilidades en un fragmento de código, con severidad, escenario de explotación, corrección y pruebas."
tags: ["seguridad", "owasp", "revisión de código", "vulnerabilidades", "appsec"]
variables: ["tipo de aplicación", "lenguaje y framework", "qué hace el código", "tu código"]
translation: "/en/programacion-datos/security-review-of-your-code-with-the-owasp-top-10"
---

Contexto: Te comparto un fragmento de código de [tipo de aplicación] escrito en [lenguaje y framework]. Esta parte se encarga de [qué hace el código] (por ejemplo: autenticación, manejo de formularios, carga de archivos, consultas a la base de datos).
Código:
[tu código]
Objetivo: Detectar vulnerabilidades antes de pasar a producción y saber qué corregir primero.
Entregable: 1) Lista de hallazgos. 2) Versión corregida de las partes afectadas. 3) Pruebas o casos de abuso que pueda usar para confirmar que cada corrección funciona.
Criterios: Revisa al menos inyección (SQL y comandos), XSS, control de acceso roto y referencias directas inseguras a objetos, manejo de secretos, validación de entradas, autenticación y sesiones, y dependencias riesgosas; relaciona cada hallazgo con su categoría del OWASP Top 10 cuando aplique. Para cada hallazgo explica cómo se explotaría en un escenario realista, porque eso ayuda a priorizar. Distingue entre vulnerabilidades confirmadas en el código y riesgos que dependen de configuración o de código que no ves. Si una parte está bien, dilo en lugar de inventar problemas para llenar la lista.
Formato: Tabla con columnas Severidad (crítica, alta, media, baja), Hallazgo, Línea o función, Categoría OWASP, Cómo se explota y Corrección; luego el código corregido en bloques y al final las pruebas en viñetas.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.
