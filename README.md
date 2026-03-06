# Morir en la Calle — Registro de prensa, Chile

Dashboard interactivo que documenta y visibiliza las muertes de personas en situación de calle en Chile, basado en un registro de prensa.

## Datos

Los datos se cargan automáticamente desde un Google Sheet publicado como CSV. Como respaldo, el archivo `index.html` incluye los datos embebidos.

**Google Sheet CSV URL:**
```
https://docs.google.com/spreadsheets/d/e/2PACX-1vRrttIj_NHTZVxNVk-FnDC0W8-3CV_s1UIaTFeIKNq_NDAjlnUaEyJWw3JA882bXAVerTZUOiowqHwV/pub?gid=1757210688&single=true&output=csv
```

## Cómo funciona

- La página lee el Google Sheet publicado en cada visita
- Si el Sheet no está disponible, usa datos embebidos como respaldo
- No requiere backend ni base de datos

## Deploy en GitHub Pages

1. Crear repositorio en GitHub
2. Subir este contenido
3. Activar GitHub Pages desde Settings → Pages → Branch: main
