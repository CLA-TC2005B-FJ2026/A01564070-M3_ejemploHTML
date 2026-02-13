# Explicación de Etiquetas HTML

Este documento explica todas las etiquetas HTML utilizadas en el archivo `index.html`.

## Estructura Básica del Documento

### `<!DOCTYPE html>`
Declaración que indica al navegador que este es un documento HTML5. Debe ser la primera línea del archivo.

### `<html lang="es">`
Etiqueta raíz que contiene todo el documento HTML. El atributo `lang="es"` especifica que el contenido está en español.

### `<head>`
Sección que contiene metadatos e información sobre el documento que no se muestra directamente en la página.

### `<meta charset="UTF-8">`
Define la codificación de caracteres UTF-8, que permite mostrar correctamente caracteres especiales y acentos del español.

### `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
Hace que la página sea responsive (adaptable a diferentes tamaños de pantalla). Es esencial para dispositivos móviles.

### `<title>`
Define el título que aparece en la pestaña del navegador: "Mi Página en GitHub".

### `<body>`
Contiene todo el contenido visible de la página web.

## Etiquetas de Encabezados

### `<h1>` - Encabezado de Nivel 1
El encabezado más importante de la página: "Mi Primera Página Web". Solo debe haber uno por página.

### `<h2>` - Encabezado de Nivel 2
Encabezados secundarios que dividen el contenido en secciones:
- "Lista de cosas que me gustan"
- "Horarios de Clases"
- "Imagen Favorita"
- "Enlace a mi perfil de GitHub"

## Etiquetas de Texto

### `<p>`
Etiqueta de párrafo. Se usa para agrupar texto en bloques. En este archivo aparece:
- "Hola, esta es mi primera página web creada en GitHub Pages."
- "Visita mi perfil aquí."

## Etiquetas de Listas

### `<ul>`
Lista desordenada (unordered list). Crea una lista con viñetas.

### `<li>`
Elemento de lista (list item). Cada `<li>` representa un punto de la lista:
- Programación
- Leer
- Viajar

## Etiquetas de Tabla

### `<table border="1">`
Crea una tabla. El atributo `border="1"` añade un borde visible de 1 píxel.

### `<tr>`
Table Row - Define una fila de la tabla.

### `<th>`
Table Header - Encabezado de columna. El texto aparece en negrita por defecto:
- Materia
- Día
- Hora

### `<td>`
Table Data - Celda de datos de la tabla. Contiene la información de cada fila.

## Etiquetas de Multimedia

### `<img src="https://via.placeholder.com/150" alt="Imagen de prueba">`
Inserta una imagen en la página.
- **src**: URL de la imagen (source)
- **alt**: Texto alternativo que se muestra si la imagen no carga o para lectores de pantalla

## Etiquetas de Enlaces

### `<a href="https://github.com/tu_usuario" target="_blank">`
Crea un hipervínculo.
- **href**: Dirección URL a la que apunta el enlace
- **target="_blank"**: Abre el enlace en una nueva pestaña del navegador

El texto "aquí" es el texto visible del enlace.

## Resumen de Etiquetas Utilizadas

| Etiqueta | Función | Cantidad |
|----------|---------|----------|
| `<!DOCTYPE>` | Declaración de tipo de documento | 1 |
| `<html>` | Contenedor principal | 1 |
| `<head>` | Metadatos del documento | 1 |
| `<meta>` | Información meta | 2 |
| `<title>` | Título de la página | 1 |
| `<body>` | Contenido visible | 1 |
| `<h1>` | Encabezado principal | 1 |
| `<h2>` | Encabezados secundarios | 4 |
| `<p>` | Párrafos | 2 |
| `<ul>` | Lista desordenada | 1 |
| `<li>` | Elementos de lista | 3 |
| `<table>` | Tabla | 1 |
| `<tr>` | Filas de tabla | 3 |
| `<th>` | Encabezados de tabla | 3 |
| `<td>` | Celdas de datos | 6 |
| `<img>` | Imagen | 1 |
| `<a>` | Enlace | 1 |

