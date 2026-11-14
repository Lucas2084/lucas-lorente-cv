# Currículum web de Lucas Lorente Arjona

Sitio estático en español con HTML y CSS, sin frameworks, dependencias, fuentes externas ni JavaScript. Abre `index.html` directamente en el navegador para verlo.

## Archivos

- `index.html`: contenido completo del currículum y enlaces de contacto.
- `style.css`: diseño adaptable, variables de personalización y estilos de impresión.
- `assets/`: carpeta para añadir `profile.jpg`; contiene instrucciones para la foto.
- `CV_Lucas_Lorente_2026.pdf`: documento original enlazado para descargar.
- `.nojekyll`: permite servir los archivos directamente con GitHub Pages.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub y sube `index.html`, `style.css`, `.nojekyll`, la carpeta `assets/` y el PDF original a su raíz. El archivo DOCX no es necesario.
2. En el repositorio, abre **Settings → Pages**.
3. Selecciona **Deploy from a branch**, la rama `main` y la carpeta **/ (root)**. Guarda la configuración.
4. Cuando termine la publicación, GitHub mostrará el enlace del sitio en esa misma sección.

Los enlaces a archivos son relativos, compatibles tanto con repositorios de proyecto como con sitios `usuario.github.io`.

## Personalizar

Modifica los colores, fuentes y espaciados en `:root`, al principio de `style.css`. Cada sección del HTML y CSS está comentada. Duplica los artículos correspondientes para incorporar experiencia o formación. Añade `assets/profile.jpg` siguiendo las instrucciones de esa carpeta.

El PDF no detalla proyectos ni certificaciones independientes; no se han inventado entradas para estas categorías. La especialización en ciberseguridad se recoge en Formación y Cambridge B2 First figura como preparación, no como certificación obtenida.

Puedes usar **Imprimir → Guardar como PDF** en el navegador: el sitio incluye estilos específicos para impresión. El enlace «Descargar CV» entrega el PDF original.
