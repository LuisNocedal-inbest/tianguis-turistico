# CreaTurismo — Tianguis Turístico México 2026

Prototipo navegable de la app oficial del Tianguis Turístico México 2026. Sitio estático (sin build): `support.js` carga React/ReactDOM y renderiza los archivos `.html`.

- `index.html` — prototipo navegable (el que ves al abrir el sitio).
- `design.html` — lienzo con todas las pantallas del diseño (splash, home, gafete, citas, avisos, etc.).
- `support.js` — runtime generado, no editar a mano.
- `uploads/` — assets pegados durante el diseño.

## Desplegar en Cloudflare Pages

1. En el dashboard de Cloudflare → **Workers & Pages → Create → Pages → Connect to Git**.
2. Elegí este repo.
3. Build settings: **framework preset "None"**, build command vacío, output directory `/` (raíz).
4. Deploy. Cada push a `main` vuelve a desplegar solo.
