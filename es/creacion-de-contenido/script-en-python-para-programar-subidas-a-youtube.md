---
title: "Script en Python para programar subidas a YouTube"
model: "ChatGPT · Claude · Gemini"
image: "creacion-de-contenido.webp"
id: "CON-0017"
lang: es
type: texto
category: "Creación de contenido: YouTube, podcast y blog"
category_slug: "creacion-de-contenido"
subcategory: "Automatización"
level: "avanzado"
description: "Obtén un script en Python que sube y programa videos con título, descripción y etiquetas desde una hoja de cálculo."
tags: ["python", "api de youtube", "automatización", "metadatos"]
variables: ["tema del canal", "formato de la hoja de cálculo", "tu nivel de programación"]
translation: "/en/creacion-de-contenido/python-script-to-schedule-youtube-uploads"
---

Contexto: Tengo videos ya editados para mi canal sobre [tema del canal] en una carpeta local, y una hoja de cálculo en [formato de la hoja de cálculo] (CSV o Google Sheets) con columnas de archivo, título, descripción, etiquetas, miniatura, lista de reproducción y fecha de publicación. Mi nivel de programación es [tu nivel de programación].
Objetivo: Subir y programar los videos en lote con sus metadatos, sin cargarlos uno por uno en YouTube Studio.
Entregable: 1) Un script en Python que use la API de datos de YouTube (v3) con autenticación OAuth, suba cada video como privado con fecha de publicación programada, asigne miniatura y lista de reproducción, y registre el resultado en un archivo de log. 2) Instrucciones de configuración: proyecto en Google Cloud, credenciales, dependencias y cómo ejecutarlo. 3) Una plantilla de descripción con llamada a la acción y espacios para enlaces.
Criterios: Valida los datos de la hoja antes de subir (que el archivo exista, la longitud del título, que la fecha sea futura) y maneja los errores sin detener todo el lote. Explica la cuota diaria de la API y cómo evitar agotarla; si tienes búsqueda web, confirma los límites vigentes y marca lo que sea estimación. Guarda las credenciales fuera del código.
Formato: Código completo en un bloque con comentarios, seguido de la guía de configuración en pasos numerados.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.
