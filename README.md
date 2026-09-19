# ¡Feliz 6° Cumpleaños, Princesa Siena!

Página web de cumpleaños para Siena (6 años), con tema de princesa, collage polaroid de 14 fotos reales, carta de amor, 6 razones y confetti mágico.

## Cómo publicar en GitHub Pages

Publicado desde la rama `main`, carpeta raíz (`/`). El archivo `.nojekyll` ya está incluido.

1. Creá un repositorio en GitHub (público).
2. Subí este proyecto a la rama `main`.
3. En **Settings → Pages**, seleccioná `Deploy from a branch` con `main / root`, guardás y listo.

La URL quedará en: `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`

## Archivos

- `index.html` — página única autocontenida (CSS y JS inline, sin dependencias de build).
- `fotosSiena/` — las 14 fotos reales usadas en el collage y el hero.
- `.nojekyll` — evita que Jekyll interfiera con la publicación.

## Ver local

Abrí `index.html` directamente en el navegador o servilo con cualquier servidor estático:

```
npx serve .
```