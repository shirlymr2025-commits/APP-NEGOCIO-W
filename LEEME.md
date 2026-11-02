# Mi Negocio — ventas, inventario, costos y caja

App para llevar un negocio pequeño desde el celular. Cada persona que la instala tiene su propio negocio y sus datos quedan guardados en su celular.

## Archivos (súbelos todos, sueltos, sin carpetas)
- `index.html` — la app
- `manifest.webmanifest` — permite instalarla como app
- `sw.js` — permite abrirla sin internet
- `icon-192.png`, `icon-512.png` — íconos
- `jspdf.umd.min.js` — genera los recibos en PDF
- `xlsx.full.min.js` — lee y crea los Excel de inventario

## Publicarla en GitHub Pages
1. Repositorio **público** → **Add file → Upload files** → sube los 7 archivos → **Commit changes**.
2. **Settings → Pages** → *Deploy from a branch* → **main** / **(root)** → **Save**.
3. Enlace: `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`

## Actualizar
Sube el `index.html` nuevo (y los demás que cambien) y en `sw.js` sube el número de `mi-negocio-vNN`. Revisa que los archivos no queden con "(1)" en el nombre. Los datos de las personas no se borran.
