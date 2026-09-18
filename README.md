# Landing Pages

Repositorio con las landing pages de la Gobernación de Sucre. Cada proyecto vive en su propia carpeta, autocontenido (un solo `index.html`, sin dependencias externas de build).

## Proyectos

| Carpeta | Descripción | URL (GitHub Pages) |
|---|---|---|
| `banco-alimentos-sucre/` | Landing del Banco de Alimentos de Sucre — Gran Donatón 2026 | `https://<usuario>.github.io/<repo>/banco-alimentos-sucre/` |

## Cómo agregar una nueva landing page

1. Crea una carpeta nueva en la raíz del repo, por ejemplo `mi-nueva-landing/`.
2. Coloca ahí un `index.html` autocontenido (HTML + CSS + JS en un solo archivo).
3. Haz commit y push. Si GitHub Pages está activo, queda disponible automáticamente en `https://<usuario>.github.io/<repo>/mi-nueva-landing/`.

## Activar GitHub Pages (una sola vez)

En GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `root`**. Guarda. En unos minutos cada carpeta con `index.html` queda publicada.

## Clonar / actualizar

```bash
git clone https://github.com/<usuario>/<repo>.git
cd <repo>
git pull
```
