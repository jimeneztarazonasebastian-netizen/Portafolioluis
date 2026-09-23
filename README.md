# Portafolio — Luis Santiago Tarazona Jiménez

Sitio estático de una sola página. Todo (imágenes, fuentes, estilos) está dentro de `index.html`.

## Publicar en Vercel

**Opción rápida (sin repo)**
1. Entra a vercel.com/new
2. Arrastra esta carpeta completa a la zona de "Deploy"
3. Listo. Vercel te da la URL.

**Opción con GitHub** (es la que usa este repo)
1. `index.html` ya está en la raíz del repo — Vercel lo detecta sin configuración extra.
2. En Vercel: New Project → Import Git Repository → selecciona este repo.
3. Framework Preset: **Other**. Build Command: vacío. Output Directory: vacío (raíz). Root Directory: `./`
4. Deploy.

## Hoja de vida (PDF)

El botón «Descargar hoja de vida» del hero apunta a `/CV_Luis_Santiago_Tarazona_ES.pdf`, y
en la versión inglesa de la página a `/CV_Luis_Santiago_Tarazona_EN.pdf` (el enlace lleva
las dos rutas en `data-href-es` y `data-href-en`, y el módulo de idioma elige).
Este proyecto **no tiene carpeta `public/`**: Vercel sirve la raíz del repo, así que los PDF
van en la raíz, junto a `index.html`, y hay que **commitearlos** para que queden publicados.

## Iconos

`favicon.ico` (16, 32 y 48 px), `icon-192.png` y `apple-touch-icon.png` salen del logo TJ
de la intro, sobre una baldosa del fondo oscuro de la página. Van enlazados en las dos
cabeceras de `index.html`: la exterior, que es la que leen buscadores y vistas previas, y
la del template.

## Dominio propio
En Vercel → Settings → Domains → Add. Si compras un dominio (ej. luissantiago.dev), apuntas los DNS que Vercel te indique.

## Actualizar el sitio
Los cambios se hacen en el diseño original y se vuelve a exportar este `index.html`.
