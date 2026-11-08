# Fichas Triples

Juego de fichas apiladas: junta 3 iguales para quitarlas. Sin anuncios, sin cuentas, sin coste.
Es una web estatica instalable como app (PWA). El progreso (nivel y racha) se guarda en el propio movil.

## Archivos (todos juntos en la raiz del repositorio)

- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png
- icon-maskable-512.png
- apple-touch-icon.png

## Publicar en GitHub Pages

1. En github.com: New repository, nombre sin espacios ni acentos (por ejemplo `fichas-triples`), Public.
2. Pulsa "uploading an existing file", sube TODOS los archivos de arriba y pulsa Commit changes.
3. Settings > Pages > Branch `main` y carpeta `/ (root)` > Save.
4. En 1 o 2 minutos estara en `https://TU-USUARIO.github.io/fichas-triples/`

## Instalarlo como app en el movil

- **Android (Chrome):** abre el enlace, menu de los tres puntos > "Instalar aplicacion" (o "Anadir a pantalla de inicio").
- **iPhone (Safari):** abre el enlace, boton Compartir > "Anadir a pantalla de inicio". Tiene que ser Safari.

Se instala con el icono de la manzana y se abre a pantalla completa, sin barra del navegador. Una vez abierto la primera vez, funciona sin internet.

## Actualizar

Edita `index.html` en GitHub (icono del lapiz) y haz commit. Si hay internet, la app se actualiza sola al abrirla (puede hacer falta abrirla dos veces).
Si anades o renombras archivos, anadelos tambien a la lista `FILES` de `sw.js`.
