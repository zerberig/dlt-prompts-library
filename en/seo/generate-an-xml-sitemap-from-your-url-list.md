---
title: "Generate an XML Sitemap From Your URL List"
model: "ChatGPT · Claude · Gemini"
image: "seo.webp"
id: "SEO-0029"
lang: en
type: text
category: "SEO"
category_slug: "seo"
subcategory: "Technical SEO"
level: "intermediate"
description: "Turn a list of URLs into a valid XML sitemap, ready to upload and submit to Search Console."
tags: ["xml sitemap", "indexing", "crawling", "code"]
variables: ["your domain", "list of URLs"]
translation: "/es/seo/genera-un-sitemap-xml-a-partir-de-tu-lista-de-urls"
---

Context: My site is [your domain] and it doesn't generate a sitemap automatically. These are the URLs I want indexed, with their last-modified date where I have it: [list of URLs].
Goal: I want a valid XML sitemap that helps search engines discover my pages.
Deliverable: 1) The complete sitemap.xml file with loc and lastmod tags. 2) A list of URLs you excluded and why (duplicates, parameters, non-HTTPS, or likely non-indexable). 3) The line I need to add to my robots.txt. 4) Short steps to upload it and submit it in Search Console.
Criteria: Include lastmod only with the real dates I gave you, because an invented date makes the file less trustworthy. Leave out priority and changefreq, since Google ignores them; if you have web search, confirm that. Use absolute, canonical URLs and well-formed XML.
Format: The sitemap in a code block, then the other three parts under headings.
