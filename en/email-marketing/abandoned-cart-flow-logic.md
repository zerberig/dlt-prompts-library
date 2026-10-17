---
title: "Abandoned Cart Flow Logic"
model: "ChatGPT · Claude · Gemini"
image: "email-marketing.webp"
id: "EML-0011"
lang: en
type: text
category: "Email Marketing & Newsletters"
category_slug: "email-marketing"
subcategory: "Automations"
level: "advanced"
description: "Define the triggers, timing, exit conditions, and incentives for your abandoned cart automation."
tags: ["abandoned cart", "automation", "ecommerce", "flows", "sales recovery"]
variables: ["type of products", "store platform", "email platform", "average order value", "possible incentive"]
translation: "/es/email-marketing/logica-del-flujo-de-carrito-abandonado"
---

Context: I run an online store selling [type of products] on [store platform], connected to [email platform]. My average order value is [average order value] and my margin lets me offer at most [possible incentive].
Goal: Set up an abandoned cart automation that recovers sales without handing discounts to people who were going to buy anyway.
Deliverable: 1) The flow described in text: trigger, wait times, emails, conditions, and exits. 2) The rules: when someone enters, when they exit (purchase, unsubscribe, return to cart), and how to keep it from clashing with other flows. 3) The incentive strategy: which email, which carts (for example, by order value or first purchase), and with what cap. 4) The metrics for evaluating the flow and when to adjust it.
Criteria: Use common wait times as a starting point and explain how to test others. The flow only applies to contacts who agreed to receive emails or where my country's law allows it. Flag as an estimate any figure you can't back up with a source.
Format: The flow as a numbered list with indents for branches; rules and incentives as bullets; metrics in a table.
If any essential information is missing, ask me up to 3 questions before you start.
