# Pevarq — Sitio web

## Estructura

- `index.html` — sitio completo (diseño fijo, no se edita desde el panel)
- `admin/` — panel de administración (Decap/Netlify CMS)
- `content/proyectos/*.json` — datos de cada proyecto (editable desde el panel)
- `content/press.json` — lista de publicaciones (editable desde el panel)
- `images/` — todas las imágenes del sitio

## Imágenes pendientes

Cada proyecto tiene imágenes con URLs de Google Drive que ya no funcionan
(Drive bloquea el acceso directo a imágenes). Desde el panel de administración,
sube las fotos reales para reemplazar esas entradas:

- 01-casa-arreygue: 7 de 9 pendientes
- 02-casa-navarro: 19 de 21 pendientes
- 03-villa-kai-kai: 24 de 26 pendientes
- 04-casa-rd: 8 de 10 pendientes (incluye el HERO en video)

La primera imagen de cada proyecto es el HERO (foto o video principal).
El resto es la galería, en el orden en que aparecen.

## Próximos pasos de migración

1. Subir esta carpeta a un repositorio de GitHub
2. Conectar el repositorio a Netlify
3. Activar Netlify Identity + Git Gateway (para que el panel /admin funcione)
4. Conectar el dominio pevarq.com
5. Entrar a pevarq.com/admin y subir las fotos/video pendientes
