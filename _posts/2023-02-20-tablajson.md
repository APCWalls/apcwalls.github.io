---
title: Tabla json
author: Alejandro Paredes
date: 2023-02-03 18:32:00 -0500
categories: [Blogging, Tutorial]
tags: [google analytics, pageviews]
---

{% for persona in site.data.personas %}
## {{ persona.nombre }} - {{ persona.formacion }} - {{persona.edad}}
{% endfor %}