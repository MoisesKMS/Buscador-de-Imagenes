# Buscador de Imagenes
App Web para la búsqueda de imágenes sin copyright usando la API de Pixabay hecha con JavaScript puro/vanilla

![Buscador de Imagenes Imagen](https://lh3.googleusercontent.com/-nsXul3y2LFY/YYSYW6dwmoI/AAAAAAAAA_M/87ziNSmvgy0nT1bKfQEIrFFtbq1uCizJACLcBGAsYHQ/s16000/01.png)
![Buscador de Imagenes Imagen](https://lh3.googleusercontent.com/-3OQmXA-Pkms/YYSYYAzeHWI/AAAAAAAAA_Q/e6LUMfE-iuYnMJkVCWGGbAt_KVGyWlOFgCLcBGAsYHQ/s16000/02.png)

## Pre-requisitos 📋
Obtener una cuenta en Pixabay para hacer uso de la API

## Instalación 🔧
Se puede correr en con LiveServer o subir a Netlify

```
Solo ejecuta index.html
```

## Configuracion ⚙️
Configurar tu Key de Pixabay para que funcione con Fecth
```
const url = `https://pixabay.com/api/?key=${key}&q=${termino}&per_page=${registrosPorPagina}&page=${paginaActual}`;
```
