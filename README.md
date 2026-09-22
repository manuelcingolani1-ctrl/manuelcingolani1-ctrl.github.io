# manuelcingolani.github.io

Landing personal de Manuel Cingolani. HTML + CSS + JS puro, sin dependencias ni build.

## Publicar en GitHub Pages (5 min)

1. Crea un repositorio **público** llamado exactamente `<tu-usuario>.github.io`
   (p. ej. `manuelcingolani.github.io`).
2. Sube todo el contenido de esta carpeta a la raíz del repo:
   ```bash
   git init && git add . && git commit -m "Landing personal"
   git branch -M main
   git remote add origin https://github.com/<tu-usuario>/<tu-usuario>.github.io.git
   git push -u origin main
   ```
3. En GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.
4. En 1–2 minutos estará en `https://<tu-usuario>.github.io`.

### Dominio propio (opcional)
Crea un archivo `CNAME` con tu dominio (p. ej. `manuelcingolani.com`), y en tu proveedor DNS
apunta registros `A` a `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
(o un `CNAME` de `www` a `<tu-usuario>.github.io`). Luego activa **Enforce HTTPS**.

## Archivos
- `index.html` — la landing
- `cv-manuel-cingolani.pdf` — CV descargable
- `favicon.svg`, `404.html`, `.nojekyll`

## Atajos de teclado en la web
`C` copia el email · `D` descarga el CV · `⌘K / Ctrl K` abre el menú de comandos
