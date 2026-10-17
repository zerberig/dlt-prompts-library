---
title: "Script para exportar comentarios de YouTube con su API"
model: "ChatGPT · Claude · Gemini"
image: "creacion-de-contenido.webp"
id: "CON-0058"
lang: es
type: texto
category: "Creación de contenido: YouTube, podcast y blog"
category_slug: "creacion-de-contenido"
subcategory: "Automatización"
level: "avanzado"
description: "Obtén un script comentado que descarga los comentarios de un video con la API de YouTube, maneja errores y los guarda en CSV."
tags: ["api de youtube", "programación", "comentarios", "javascript", "python"]
variables: ["lenguaje de programación", "nivel de programación"]
translation: "/en/creacion-de-contenido/script-to-export-youtube-comments-with-the-api"
---

Contexto: Quiero analizar los comentarios de mis videos de YouTube. Programaré en [lenguaje de programación] y mi nivel es [nivel de programación]. Ya tengo o puedo crear una clave de API en Google Cloud.
Objetivo: Necesito un script que descargue todos los comentarios principales y sus respuestas de un video y los guarde en un archivo CSV para analizarlos después.
Entregable: 1) El código completo usando la API de datos de YouTube (endpoint de hilos de comentarios), que reciba el ID o la URL del video, recorra todas las páginas de resultados y guarde autor, texto, fecha, me gusta y si es respuesta. 2) Manejo de errores para clave inválida, video inexistente, comentarios desactivados, cuota agotada y fallos de red, con reintentos razonables. 3) Instrucciones breves para configurar la clave de forma segura (variable de entorno) y ejecutar el script. 4) Una nota sobre el costo en cuota por ejecución.
Criterios: Código legible y con comentarios que expliquen cada bloque, porque lo voy a mantener yo. Usa solo funciones oficiales de la API y respeta sus términos de uso. Si tienes búsqueda web, verifica la versión actual de la API y de la librería cliente.
Formato: Un bloque de código, seguido de las instrucciones en lista numerada.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.
