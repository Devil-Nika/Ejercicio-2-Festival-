EJERCICIO 2 – Sitio web en HTML con 5 páginas secundarias
Temática del sitio
“Expo Joven Full Stack”
El sitio web representará una exposición estudiantil donde se presentan:
información general del evento,


talleres,


proyectos estudiantiles,


galería multimedia,


inscripción,


contacto.



Estructura de carpetas del proyecto
nombre-del-proyecto/
├── index.html
│   
├── pages/
│   ├── talleres.html
│   ├── proyectos.html
│   ├── galeria.html
│   ├── inscripcion.html
│   └── contacto.html
├── img/
│   ├── logo.png
│   ├── portada.jpg
│   ├── taller1.jpg
│   ├── taller2.jpg
│   └── proyecto1.jpg
└── assets/
   ├── audio/
   │   └── bienvenida.mp3
   └── video/
       └── presentacion.mp4

Objetivo del ejercicio
Construir un sitio web de varias páginas usando etiquetas HTML semánticas y de contenido, respetando la estructura de carpetas dada.

Consigna general para el estudiante
Crear un sitio web de al menos 6 páginas en total:
1 página principal: index.html


5 páginas secundarias:


talleres.html


proyectos.html


galeria.html


inscripcion.html


contacto.html


Todas las páginas deben estar conectadas mediante un menú de navegación.
Requisitos obligatorios
1. Estructura del sitio
En todas las páginas debe aparecer:
<html>


<head>


<body>


<header>


<nav>


<main>


<footer>


Además, según corresponda, deben usar:
<section>


<article>


<aside>


<div>



2. Etiquetas de texto y organización
A lo largo del sitio deben aparecer:
al menos un <h1> por página


subtítulos con <h2> o <h3>


párrafos con <p>


enlaces con <a>


listas con <ul> o <ol>


elementos de lista con <li>


uso de <span>


uso de <strong>


uso de <em>


al menos un <br>



3. Multimedia e interactividad
En el sitio deben incluir:
al menos 3 imágenes con <img>


1 audio con <audio>


1 video con <video>


1 formulario con <form>


distintos tipos de <input>


1 <button>


1 <select>


1 <table>



4. Atributos obligatorios
Deben usar correctamente varios de estos atributos:
id



title


lang


href


src


alt


target


value


placeholder


required



Desarrollo sugerido por archivo
1) index.html – Página de inicio
Contenido sugerido
Logo del evento.


Título principal: Expo Joven Full Stack 2026.


Breve bienvenida.


Menú de navegación hacia las demás páginas.


Una imagen de portada.


Una sección con presentación general del evento.


Un aside con “Próximas fechas importantes”.


Un pie de página con datos institucionales.


Etiquetas que pueden aplicar
<header>


<nav>


<main>


<section>


<aside>


<footer>


<img>


<h1>, <h2>, <p>


<a>


<ul>, <li>


<strong>, <em>, <span>



2) pages/talleres.html
Contenido sugerido
Mostrar los talleres que habrá en la expo:
HTML y CSS


JavaScript


PHP y MySQL


Cada taller puede estar dentro de un <article>.
Debe incluir
una lista ordenada o desordenada de talleres,


una breve descripción por taller,


imágenes de talleres,


un enlace para volver al inicio.


Etiquetas clave
<section>


<article>


<h2>, <h3>


<p>


<ul> o <ol>


<li>


<img>


<a>



3) pages/proyectos.html
Contenido sugerido
Una página con proyectos destacados de estudiantes.
Cada proyecto puede incluir:
nombre del proyecto,


descripción,


tecnologías usadas,


enlace ficticio a repositorio o demo.


Debe incluir
al menos 2 <article>


una tabla comparativa de proyectos


Tabla sugerida
Columnas:
Proyecto


Lenguajes usados


Estado


Equipo


Etiquetas clave
<article>


<table>


<tr>


<td>


<p>


<a>


<strong>



4) pages/galeria.html
Contenido sugerido
Una galería multimedia del evento.
Debe incluir
varias imágenes,


un video de presentación,


un audio de bienvenida.


Etiquetas clave
<img>


<video>


<audio>


<section>


<div>


Ejemplo de contenido
Fotos del salón


Video promocional


Audio con mensaje de bienvenida del equipo organizador



5) pages/inscripcion.html
Contenido sugerido
Formulario de inscripción para participar en la expo.
Debe incluir
Un formulario con:
nombre


apellido


correo electrónico


edad


curso de interés


turno preferido


aceptación de condiciones


botón enviar


Etiquetas clave
<form>


<input>


<select>


<button>


Atributos que deberían aparecer
placeholder


required


value


id


class



6) pages/contacto.html
Contenido sugerido
Página de contacto institucional.
Debe incluir
dirección


correo


teléfono


mapa o imagen de referencia


formulario breve de consulta


enlaces a redes o sitios externos


Etiquetas clave
<section>


<p>


<a>


<img>


<form>


<input>


<button>


Y aquí puede usarse:
target="_blank" en enlaces externos


title para dar información extra al pasar el mouse



Etiquetas que se pide usar sí o sí
Estructura y contenido semántico
<html>


<head>


<body>


<header>


<nav>


<main>


<section>


<article>


<aside>


<footer>


<div>


Texto y organización
<h1> a <h6>


<p>


<a>


<ul> o <ol>


<li>


<span>


<strong>


<em>


<br>


Multimedia y formularios
<img>


<video>


<audio>


<form>


<input>


<button>


<select>


<table>



Atributos mínimos que deben aparecer en el trabajo
lang="es" en <html>


href en enlaces


src en imágenes, audio y video


alt en imágenes


target="_blank" en al menos un enlace externo


id en algunos elementos


class en varios elementos


title en al menos un enlace o imagen


placeholder en inputs


required en campos obligatorios


value en algún input o botón



Propuesta de consigna redactada para entregar al grupo
Consigna
Crear un sitio web en HTML llamado Expo Joven Full Stack usando la estructura de carpetas indicada por el docente.
El sitio debe tener:
una página de inicio,


cinco páginas secundarias,


navegación entre todas las páginas,


contenido organizado semánticamente,


imágenes, audio, video, tabla y formulario.


No se utilizará CSS ni JavaScript para resolver la actividad. El objetivo es practicar la estructura HTML, la organización de archivos y el uso correcto de etiquetas y atributos.


