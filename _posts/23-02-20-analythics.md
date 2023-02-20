---
title: Google Analythics 
nombre: True
date: 2023-02-20 11:33:00 +0800
categories: [Blogging, Tutorial]
tags: [analythics]

---

## Como poner Google Analytics en un Jekyll con el tema Chirpy

El procedimiento es super sencillo. Tan solo tenemos que crearnos una cuenta de Google Analytics. Y cuando tengamos el id de nuestra página, tan solo lo tenemos que pegar en el _config.yml


![Desktop View](/assets/img/ga1.png)

![Desktop View](/assets/img/ga3.png)

![Desktop View](/assets/img/ga2.png)

## En caso de ser para otro tema

<h2>Cómo añadir Google Analytics a tu sitio web Jekyll</h2>
<h3>Paso 1: Crear una cuenta de Google Analytics</h3>
Si aún no tienes una cuenta de Google Analytics, necesitarás crear una. Para hacerlo, sigue los siguientes pasos:

Visita Google Analytics y haz clic en "Iniciar sesión".
Si ya tienes una cuenta de Google, ingresa tus credenciales. Si no, crea una cuenta nueva.
En la página de inicio de Google Analytics, haz clic en "Regístrate".
Sigue las instrucciones para configurar tu cuenta y tu propiedad.

<h3>Paso 2: Obtener tu ID de seguimiento</h3>
Una vez que hayas configurado tu cuenta y propiedad en Google Analytics, necesitarás obtener tu ID de seguimiento. Sigue estos pasos para hacerlo:


En Google Analytics, haz clic en "Administrar" en la parte inferior izquierda de la pantalla.
En la columna de "Cuenta", selecciona la cuenta que deseas utilizar.
En la columna de "Propiedad", selecciona la propiedad que deseas utilizar.
En la columna de "Información de seguimiento", haz clic en "Información de seguimiento".
Copia el código de seguimiento que se muestra. Debería tener un formato como el siguiente:
html

![Desktop View](/assets/img/ga4.png)

<h3>Paso 3: Añadir el código de seguimiento a tu sitio web Jekyll</h3>
Ahora que tienes tu ID de seguimiento, necesitarás añadir el código de seguimiento a tu sitio web Jekyll. Sigue estos pasos para hacerlo:

Abre el archivo default.html (o el archivo de diseño que estés utilizando) en la carpeta _layouts de tu sitio Jekyll.
Añade el siguiente código justo antes del cierre de la etiqueta head:
html

![Desktop View](/assets/img/ga5.png)

Reemplaza ID_DE_SEGUIMIENTO con el ID de seguimiento que obtuviste en el paso anterior.
Paso 4: Comprobar si el seguimiento está funcionando
Una vez que hayas añadido el código de seguimiento a tu sitio web Jekyll, podrás comprobar si está funcionando correctamente. Sigue estos pasos para hacerlo:


Visita tu sitio web Jekyll.
En Google Analytics, haz clic en "Informes".
En la sección de "Tiempo real", haz clic en "Visión general".
Si todo está configurado correctamente, deberías ver un contador que indica que hay una persona visitando tu sitio web en ese momento