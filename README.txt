TOMÁS OVIEDO — APP DE TURNOS

Esta carpeta contiene una PWA instalable en Android y iPhone.

ARCHIVOS PRINCIPALES
- index.html: página de turnos.
- manifest.json: configuración de instalación como aplicación.
- sw.js: funcionamiento offline y caché.
- icon-192.png / icon-512.png / icon-1024.png: iconos de la app.

IMPORTANTE
Para instalarla como aplicación, debe publicarse mediante HTTPS (por ejemplo GitHub Pages). No alcanza con abrir index.html haciendo doble clic en la PC, porque el Service Worker necesita un origen seguro.

ANDROID
1. Publicá la carpeta en GitHub Pages.
2. Abrí la URL en Chrome.
3. Elegí “Instalar aplicación” o “Agregar a pantalla de inicio”.

iPHONE
1. Abrí la URL en Safari.
2. Tocá Compartir.
3. Elegí “Agregar a pantalla de inicio”.

DATOS DE TURNOS
La versión actual guarda los turnos en localStorage del dispositivo/navegador. Eso significa que los turnos NO se sincronizan automáticamente entre distintos teléfonos. Para una agenda compartida entre varios dispositivos hace falta conectar una base de datos/backend.
