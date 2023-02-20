---
title: Tabla de un archivo JSON
nombre: True
date: 2023-02-19 11:34:00 +0800
categories: [Blogging, Tutorial]
tags: [tabla, json]
---

{% for persona in site.data.personas %}
## {{ persona.nombre }} - {{ persona.formacion }} - {{persona.edad}}
{% endfor %}