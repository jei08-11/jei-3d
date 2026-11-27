AIM ARENA 3D — proyecto PWA

Archivos:
- index.html: aplicación
- manifest.webmanifest: configuración instalable
- sw.js: caché para abrirla después sin conexión
- icon.svg: icono

PUBLICAR EN GITHUB PAGES:
1. Crea un repositorio nuevo en GitHub.
2. Sube los 4 archivos directamente a la raíz del repositorio (no dentro de otra carpeta).
3. En Settings > Pages, selecciona Deploy from a branch.
4. Selecciona la rama main y la carpeta /(root), y guarda.
5. Espera a que GitHub Pages publique el sitio.
6. Abre el enlace https://TU-USUARIO.github.io/TU-REPOSITORIO/ en Chrome Android.
7. Menú ⋮ > Instalar aplicación o Añadir a pantalla principal.

La primera carga necesita internet. Luego el service worker guarda los archivos para abrir la app offline.
Es un aim trainer independiente con blancos ficticios; no modifica Blood Strike.
