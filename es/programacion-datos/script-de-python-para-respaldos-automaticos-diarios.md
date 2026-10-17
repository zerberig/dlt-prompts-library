---
title: "Script de Python para respaldos automáticos diarios"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0014"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Automatización"
level: "intermedio"
description: "Genera un script de Python que comprime una carpeta, guarda respaldos con fecha, borra los antiguos y corre solo."
tags: ["python", "automatización", "respaldos", "scripts", "cron"]
variables: ["carpeta de origen", "destino del respaldo", "sistema operativo", "cuántos respaldos conservar"]
translation: "/en/programacion-datos/python-script-for-automatic-daily-backups"
---

Contexto: Quiero respaldar cada día la carpeta [carpeta de origen] en [destino del respaldo] (disco externo, carpeta de red o carpeta sincronizada con la nube). Uso [sistema operativo] y quiero conservar [cuántos respaldos conservar].
Objetivo: Olvidarme de los respaldos manuales y saber siempre si el último funcionó.
Entregable: 1) Un script de Python que reciba origen y destino como argumentos, comprima la carpeta en .zip o .tar.gz con la fecha en el nombre, borre los respaldos más antiguos según la cantidad a conservar y registre en un log cada ejecución y cada error. 2) Cómo programarlo para que corra solo cada día en mi sistema operativo (cron, Programador de tareas o launchd). 3) Cómo probarlo y cómo restaurar un respaldo.
Criterios: Usa solo la biblioteca estándar de Python para que funcione sin instalar nada. Maneja los errores comunes (carpeta inexistente, disco lleno, permisos) con mensajes claros, y verifica que el archivo comprimido se pueda abrir antes de borrar respaldos viejos, porque un respaldo corrupto da una falsa seguridad.
Formato: El script completo en un bloque de código con comentarios, seguido de los puntos 2 y 3 numerados.
