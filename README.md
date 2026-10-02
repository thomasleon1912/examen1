# Parcial Práctico - HTML y CSS

Repositorio con la estructura base y estilos para la evaluación práctica de desarrollo web.

## Estructura del Proyecto

* `index.html`: Archivo principal con la estructura de la página (menú, tarjetas, formulario de contacto y tabla de notas).
* `style.css`: Hoja de estilos con la maquetación y diseño visual básico.
* `yo/`: Carpeta que contiene las imágenes de recursos locales utilizadas en el proyecto (`yo.jpg` y `novia.jpg.jpeg`).

## Sintaxis Básica de HTML Utilizada

* **Estructura base:** Todo documento arranca con `<!DOCTYPE html>`, seguido de la etiqueta `<html>`, el `<head>` (para metadatos y enlaces de estilo) y el `<body>` (lo que se ve en pantalla).
* **Secciones semánticas:** Uso de etiquetas claras como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<table>` y `<footer>` para ordenar el contenido.
* **Formularios:** Etiquetas como `<form>`, `<label>`, `<input>` y `<textarea>` para capturar datos del usuario.
* **Multimedia:** Inserción de imágenes mediante la etiqueta `<img src="..." alt="...">`.

## Sintaxis Básica de CSS Utilizada

* **Selector universal (`*`):** Para limpiar márgenes y paddings por defecto de los navegadores (`margin: 0; padding: 0; box-sizing: border-box;`).
* **Selectores de etiqueta y clase:** Estilos aplicados directamente a elementos (`body`, `header`, `footer`) o mediante clases (`.navbar`, `.card`, `.tabla-notas`).
* **Flexbox:** Uso de `display: flex` para alinear elementos horizontalmente, repartir espacios (`justify-content`) y alinear verticalmente (`align-items`).
* **Diseño de tablas y formularios:** Bordes colapsados (`border-collapse: collapse`), anchos al 100% y adaptación de inputs para mantener una interfaz limpia y legible.