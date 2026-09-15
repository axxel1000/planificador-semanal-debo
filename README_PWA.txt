# Planificador Semanal — PWA instalable

Esta versión está preparada como **PWA instalable** en Chrome Android.

Archivos agregados:
- `manifest.webmanifest`
- `sw.js`
- `icons/icon-192.png`
- `icons/icon-512.png`

## Importante para GitHub Pages
La aplicación debe publicarse por **HTTPS** en GitHub Pages. No se puede instalar como PWA abriendo directamente el archivo `.html` desde Descargas.

Una vez publicada en GitHub Pages:
1. Abrir la URL de la aplicación en Chrome Android.
2. Esperar unos segundos con la página abierta.
3. En el menú de Chrome debería aparecer **Instalar aplicación** (en algunas versiones puede figurar como **Agregar a pantalla de inicio**).
4. Elegir **Instalar**.

El `start_url` y el `scope` son relativos (`./`) para que funcionen también cuando GitHub Pages publique el proyecto dentro de una ruta como `/nombre-del-repositorio/`.

La sincronización Firebase existente no se modifica.
