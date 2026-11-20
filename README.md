# DINGO FIX · Landing (versión para mostrar al cliente)

Sitio estático: no necesita instalar nada. Abrí `index.html` o publicalo con GitHub Pages.

## Publicar en GitHub Pages
1. En GitHub: **New repository** → nombre `dingofix-web` → Public → Create.
2. Subí **todo el contenido de esta carpeta** (`index.html`, `assets/`, `.nojekyll`, `README.md`) a la raíz del repo.
3. **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, carpeta `/ (root)` → Save.
4. En 1 o 2 minutos queda en `https://TU-USUARIO.github.io/dingofix-web/`.

## Notas
- Tiene `noindex`: Google no lo muestra mientras sea una versión de prueba. Quitá la línea `<meta name="robots" ...>` de `index.html` al salir en vivo.
- Las tipografías Teko y Oswald vienen de Google Fonts (necesita internet). Geometric 212 está en `assets/fonts`.
- Pendientes de contenido: dirección y horarios de la tienda, fotos y precios de equipos en venta.
