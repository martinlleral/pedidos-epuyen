# Pedidos Epuyen — Formulario de Pedidos Solidarios

## Qué es
Formulario web para tomar pedidos de pizza solidaria con integración a Google Sheets via Google Apps Script.

## Stack
- HTML5 + JavaScript vanilla
- Tailwind CSS (CDN)
- Google Apps Script (backend)
- Google Sheets (base de datos)

## Estructura
- **Archivo único**: `index.html`
- Mobile-first, validación nativa
- Sin package.json — sin npm

## Deploy
- GitHub Pages via GitHub Actions
- URL: https://martinlleral.github.io/pedidos-epuyen
- Repo público

## Seguridad
- Google Apps Script URL hardcodeada (riesgo bajo evaluado: datos operativos, no sensibles)
- Pendiente: validación server-side en Apps Script (origin, rate limiting, token)
- `SCRIPT_URL` en línea ~101

## Convenciones
- HTML monolítico
- Tailwind via CDN
- Fetch con mode: 'no-cors' (limitación de Apps Script)
