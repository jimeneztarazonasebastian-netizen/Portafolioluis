# Portafolio — Luis Santiago Jiménez

Sitio estático de una sola página. Todo (imágenes, fuentes, estilos) está dentro de `index.html`.

## Publicar en Vercel

**Opción rápida (sin repo)**
1. Entra a vercel.com/new
2. Arrastra esta carpeta completa a la zona de "Deploy"
3. Listo. Vercel te da la URL.

**Opción con GitHub**
1. Crea un repo nuevo (ej. `portafolio`) y sube el contenido de esta carpeta a la raíz.
2. En Vercel: New Project → Import Git Repository → selecciona el repo.
3. Framework Preset: **Other**. Build Command: vacío. Output Directory: vacío (raíz).
4. Deploy.

## Dominio propio
En Vercel → Settings → Domains → Add. Si compras un dominio (ej. luissantiago.dev), apuntas los DNS que Vercel te indique.

## Actualizar el sitio
Los cambios se hacen en el diseño original y se vuelve a exportar este `index.html`.
