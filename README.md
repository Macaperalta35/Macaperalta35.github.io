# macaperalta35.github.io

Sitio raíz de `https://macaperalta35.github.io`. Publica el archivo de verificación de la app **Refugio** en Google Play:

https://macaperalta35.github.io/.well-known/assetlinks.json

| Archivo | Para qué |
|---|---|
| `.well-known/assetlinks.json` | Huellas SHA-256 de Play Console para `io.github.macaperalta35.refugio`. Android lo lee para abrir la app sin la barra del navegador |
| `.nojekyll` | Para que GitHub Pages publique la carpeta `.well-known` |
| `index.html` | Redirige la raíz a la app en `/RefugioAPP/` |

El archivo se genera con `docs/play-store/sitio-raiz/generar-assetlinks.mjs` del repositorio RefugioAPP.
Si cambian las huellas en Play Console (por ejemplo, al restablecer la clave de subida), hay que regenerarlo y actualizarlo aquí.
