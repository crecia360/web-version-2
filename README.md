# Crecia360 — Landing v2

Sitio estático (HTML + CSS + JS vanilla, un solo `index.html`). Sin build, sin dependencias.

```
index.html          landing completa (CSS y JS incluidos)
vercel.json         caché de assets y cabeceras básicas
favicon.ico
assets/             video del hero, imágenes, logo y favicons
```

## Probar en local

```bash
npx serve .
```

## Publicar

1. Subir esta carpeta a un repositorio de GitHub.
2. En Vercel: Add New Project, importar el repositorio. Framework Preset: Other. Sin build command ni output directory.
3. Dominio: agregar `crecia360.com` en Settings > Domains.

Las etiquetas Open Graph y el JSON-LD apuntan a `https://crecia360.com`; si el dominio cambia, actualizarlas en `index.html`.
