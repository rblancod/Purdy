# Purdy · Kit Digital de Asistencias

Landing page estática (`index.html`) para el Kit Digital de Asistencias de Purdy.

## Ver en línea

El sitio se publica con GitHub Pages mediante el workflow en
`.github/workflows/pages.yml`, que se dispara en cada push a `main`.

Para activarlo la primera vez:

1. Ve a **Settings → Pages** en el repositorio.
2. En **Build and deployment**, selecciona **Source: GitHub Actions**.
3. Al hacer merge de esta rama a `main`, el workflow publicará el sitio
   automáticamente en `https://<usuario>.github.io/<repositorio>/`.

## Desarrollo local

Al ser un HTML autocontenido (sin dependencias externas más allá de
Google Fonts), basta con abrir `index.html` en el navegador.
