# Catherine Makeup

Landing page de Catherine, maquilladora profesional en Venezuela. Sitio estático en un solo archivo (`index.html`), sin build.

**Publicación:** GitHub Pages desde la rama `main` → https://daflohe.github.io/catherine-makeup/

## Estructura

| Archivo | Uso |
|---|---|
| `index.html` | Página completa (HTML + CSS + JS inline) |
| `robots.txt`, `sitemap.xml` | Indexación |
| `assets/img/` | Fotos y videos reales (pendientes) |

## Datos editables

Al inicio del `<script>` en `index.html`:

- `CONFIG`: WhatsApp (ya es el real), Calendly, Instagram, TikTok y Facebook (pendientes, son de ejemplo).
- `SERVICES` y `COURSES`: nombres, descripciones y precios en USD (precios de referencia, por confirmar).
- `SHOTS`: piezas del portafolio. Hoy son degradados de relleno; reemplazar por fotos en `assets/img/`.

## Pendientes de SEO

- [ ] Dominio propio y actualizar `canonical`, `og:url`, `sitemap.xml`, `robots.txt` y el JSON-LD.
- [ ] `og:image` (1200×630) y fotos reales con `alt` descriptivo, en WebP y con `loading="lazy"`.
- [ ] Ciudad real en el título, la descripción y `address` del JSON-LD (búsquedas locales: "maquilladora en [ciudad]").
- [ ] Perfil de Google Business y enlaces `sameAs` a redes en el JSON-LD cuando existan.
- [ ] Revisar Core Web Vitals (las fuentes vienen de Google Fonts; el fondo animado es un `<canvas>`).
- [ ] Registrar el sitio en Google Search Console y enviar el sitemap.
