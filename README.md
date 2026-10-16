# Cavaliere – Links

Página de enlaces (estilo linktree) de Cavaliere para la bio de Instagram. HTML estático, sin build.

## Estructura
- `index.html` – la página
- `assets/` – logo y fotos de la Colección Colombia
- `vercel.json` – configuración de Vercel (caché de imágenes)

## Editar
- **Número de WhatsApp:** al final de `index.html`, `const WHATSAPP = "573045346079";` (código de país + número, sin + ni espacios).
- **Precios / textos:** buscar `$120.000` o `$265.000` en `index.html`.
- **Mensajes de cada botón:** atributo `data-msg` de cada botón.

## Desplegar en Vercel
1. Sube esta carpeta a un repositorio de GitHub.
2. En vercel.com → Add New → Project → importa el repositorio.
3. Framework Preset: **Other**. Sin Build Command ni Output Directory (déjalos vacíos).
4. Deploy. Cada cambio que subas a GitHub se publica solo.
