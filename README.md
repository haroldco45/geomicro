# GeoMicro — Geopolitica & Economia con IA

PWA de microaprendizaje geopolitico con Claude IA integrado.
Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados

## Despliegue en Netlify

1. Arrastra esta carpeta a netlify.com/drop  
   O conecta el repo de GitHub a Netlify

2. En Netlify → Site settings → Environment variables:
   - Key: `ANTHROPIC_API_KEY`
   - Value: tu API key de Anthropic (sk-ant-...)

3. Listo — la IA funciona sin CORS

## Estructura
- `index.html` — App completa PWA
- `netlify/functions/ai.js` — Proxy seguro a Claude API
- `netlify.toml` — Configuracion de Netlify
