
# CBDIO Dashboard – Starter (GitHub Pages)

## ¿Qué es esto?
Un paquete listo para publicar gratis en **GitHub Pages**. Es 100% cliente: la gente sube su Excel desde el navegador, se procesa localmente, y puede exportar PDF/PPTX/snapshot. No hay servidor ni costo.

## Publicar en 2 minutos
1. Crea una cuenta en GitHub (si no tienes).
2. Crea un repositorio nuevo, por ejemplo: `cbdio-dashboard`.
3. Sube **index.html**, **.nojekyll** y este **README.md** al repo (puedes arrastrar y soltar en la UI de GitHub).
4. Ve a **Settings → Pages**:
   - **Source**: “Deploy from a branch”
   - **Branch**: `main` / `/root`
   - Guarda. Espera ~1–3 minutos.
5. Tu URL quedará como: `https://<tu-usuario>.github.io/cbdio-dashboard/`

> Si prefieres, también puedes publicar en Cloudflare Pages o Netlify (gratis), pero GitHub Pages es el más simple.

## Estructura mínima
```
index.html
README.md
.nojekyll
```

## Tips
- Si no carga, revisa que el archivo se llame **index.html** y que Pages apunte a la **carpeta root** del branch `main`.
- Si las librerías CDN están bloqueadas en tu red, abre desde otra red o habilita acceso a `cdn.jsdelivr.net` / `unpkg.com`.
- Puedes cambiar el título y el logo editando `index.html`.

## Privacidad
Todo el procesamiento del Excel ocurre en el navegador del usuario. El archivo **NO** se envía a ningún servidor.

---

Hecho con ❤️ para CBDIO.
