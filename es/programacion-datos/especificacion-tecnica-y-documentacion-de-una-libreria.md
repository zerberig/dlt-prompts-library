---
title: "Especificación técnica y documentación de una librería"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0051"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Documentación técnica"
level: "avanzado"
description: "Obtén un documento de diseño con API pública, decisiones, versionado, pruebas y un borrador de README."
tags: ["especificación técnica", "documentación de api", "librerías", "diseño de software", "readme"]
variables: ["propósito de la librería", "lenguaje", "quién la usará", "requisitos o notas iniciales"]
translation: "/en/programacion-datos/technical-spec-and-documentation-for-a-library"
---

Contexto: Vamos a crear una librería de [propósito de la librería] en [lenguaje], dirigida a [quién la usará]. Esto es lo que sabemos hasta ahora: [requisitos o notas iniciales].
Objetivo: Un documento de diseño que el equipo pueda revisar antes de implementar y que después sirva como base de la documentación pública.
Entregable: 1) Propósito, alcance y lo que la librería no hará. 2) Diseño de la API pública: clases o funciones, firmas, parámetros, valores de retorno, errores que puede lanzar y un ejemplo de uso de cada una. 3) Decisiones de diseño internas y alternativas descartadas. 4) Compatibilidad, dependencias y política de versionado semántico. 5) Estrategia de pruebas. 6) Un borrador de README con instalación, inicio rápido y ejemplos.
Criterios: Diseña la API desde el punto de vista de quien la usa: nombres claros, valores por defecto sensatos y pocas formas de hacer lo mismo, porque una API pública es difícil de cambiar después. Los ejemplos deben ser código ejecutable, no pseudocódigo. Marca las preguntas abiertas que el equipo debe decidir.
Formato: Documento en Markdown con encabezados numerados, firmas y ejemplos en bloques de código y la API en una tabla con columnas Elemento, Firma, Descripción y Errores.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.
