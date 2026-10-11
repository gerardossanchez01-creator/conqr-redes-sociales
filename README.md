# Conqr. — Landing "Agencia de Redes Sociales" (demo)

Réplica de estilo de la Home de [conqr.mx](https://www.conqr.mx), adaptada y **optimizada para SEO** como landing del servicio de **Agencia de Redes Sociales / Social Media**.

Demo para presentación a cliente. No es el sitio de producción.

## Qué incluye

- **Estilo fiel a Conqr.**: fondo negro, tipografía Helvetica Bold en blanco, titulares grandes, acentos rojo/azul/cian, animaciones de scroll-reveal y un "toroide" (anillo degradado) recreado en CSS que evoca el hero original.
- **SEO on-page**: `<title>` y meta description orientados a "agencia de redes sociales en México", Open Graph/Twitter Cards, canonical, un solo `<h1>`, jerarquía de encabezados, `lang="es"`.
- **Datos estructurados (Schema.org)**: `ProfessionalService` + `FAQPage` — pensado para mejorar la elegibilidad en resultados enriquecidos y en los resúmenes de IA (AI Overviews).
- **Accesibilidad**: skip-link, `aria-*`, soporte de `prefers-reduced-motion`.
- **Sin dependencias**: HTML + CSS + JS vanilla. Carga rápida.

## Estructura

```
index.html    Página (contenido + SEO + schema)
styles.css    Estilos (design system en variables CSS)
main.js       Scroll-reveal, contadores y menú móvil
```

## Ver en local

```bash
cd conqr-redes-sociales
python3 -m http.server 8777
# abrir http://localhost:8777
```

## Notas para producción

- Quitar `<meta name="robots" content="noindex">` del `<head>` cuando se publique de verdad (ahora está en **noindex** para no competir ni duplicar contenido con el sitio real durante la demo).
- Sustituir los tiles de portafolio por casos y creatividades reales.
- Reemplazar los enlaces de contacto/redes por los definitivos.
- Las fuentes Helvetica reales de Conqr. son de licencia; aquí se usa el stack `Helvetica Neue, Helvetica, Arial` para una apariencia equivalente sin costo de licencia.

---
Demo creada para Conqr. · 2026
