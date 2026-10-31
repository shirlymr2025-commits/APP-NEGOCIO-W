# Mi Negocio — app de ventas, inventario y costos

App para llevar un negocio pequeño desde el celular: ventas, inventario por receta, gastos fijos y ganancia real. Cada persona que la instala tiene su propio negocio, y sus datos quedan guardados en su celular.

## Archivos
- `index.html` — la app completa
- `manifest.webmanifest` — permite instalarla como app (nombre, ícono, colores)
- `sw.js` — permite abrirla sin internet
- `icon-192.png`, `icon-512.png` — íconos

## Publicarla gratis en GitHub Pages
1. Crea una cuenta en github.com.
2. Toca **New repository**, ponle un nombre (ej: `mi-negocio`), márcalo como **Public** y créalo.
3. Toca **Add file → Upload files** y sube los 5 archivos. Toca **Commit changes**.
4. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama **main**, carpeta **/(root)** y toca **Save**.
5. En 1 o 2 minutos aparece el enlace: `https://TU-USUARIO.github.io/mi-negocio/`

## Instalarla en el celular
- **Android (Chrome):** abre el enlace → menú ⋮ → **Instalar app** o **Agregar a pantalla principal**.
- **iPhone (Safari):** abre el enlace → botón Compartir → **Agregar a inicio**.

## Copias de respaldo
Los datos viven solo en el celular de cada persona. En **Ajustes (engranaje) → Descargar copia** se guarda un archivo que se puede enviar por WhatsApp o subir a Drive. En un celular nuevo: abrir la app → **Ya tengo una copia de respaldo**.

## Actualizar la app
Sube el `index.html` nuevo al mismo repositorio y cambia en `sw.js` la línea `mi-negocio-v1` por `mi-negocio-v2` (y así sucesivamente). Los datos de las personas no se borran al actualizar.
