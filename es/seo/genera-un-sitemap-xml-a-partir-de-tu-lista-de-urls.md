---
title: "Genera un sitemap XML a partir de tu lista de URLs"
model: "ChatGPT · Claude · Gemini"
image: "seo.webp"
id: "SEO-0029"
lang: es
type: texto
category: "SEO y posicionamiento"
category_slug: "seo"
subcategory: "SEO técnico"
level: "intermedio"
description: "Convierte una lista de URLs en un sitemap XML válido, listo para subir y enviar a Search Console."
tags: ["sitemap xml", "indexación", "rastreo", "código"]
variables: ["tu dominio", "lista de URLs"]
translation: "/en/seo/generate-an-xml-sitemap-from-your-url-list"
---

Contexto: Mi sitio es [tu dominio] y no genera un sitemap de forma automática. Estas son las URLs que quiero que se indexen, con su fecha de última modificación si la tengo: [lista de URLs].
Objetivo: Quiero un sitemap XML válido que ayude a los buscadores a descubrir mis páginas.
Entregable: 1) El archivo sitemap.xml completo con las etiquetas loc y lastmod. 2) Una lista de URLs que excluiste y por qué (duplicadas, con parámetros, sin HTTPS o que parezcan no indexables). 3) La línea que debo agregar a mi robots.txt. 4) Pasos breves para subirlo y enviarlo en Search Console.
Criterios: Incluye lastmod solo con las fechas reales que te di, porque una fecha inventada le resta confiabilidad al archivo. Omite priority y changefreq, ya que Google las ignora; si tienes búsqueda web, confirma ese dato. Usa URLs absolutas y canónicas, y XML bien formado.
Formato: El sitemap en un bloque de código y después las otras tres partes con encabezado.
