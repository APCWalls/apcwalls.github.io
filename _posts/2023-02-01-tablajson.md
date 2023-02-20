---
title: Tabla de un archivo JSON
nombre: True
date: 2023-02-19 11:34:00 +0800
categories: [Blogging, Tutorial]
tags: [tabla, json]
---

<table>
    <tr>
        <th>Nombre</th>
        <th>Edad</th>
        <th>Sexo</th>
    </tr>
{% for persona in site.data.personas %}
<tr>
<td>{{ persona.nombre }}</td>
<td>{{ persona.edad }}</td>
<td>{{ persona.sexo }}</td>
</tr>
{% endfor %}