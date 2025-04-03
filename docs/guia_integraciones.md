# 🌐 Guía de Integraciones Externas para GORTAZAR Legal Advisors

Este documento resume posibles integraciones externas compatibles con GitHub Pages y Jekyll, cumpliendo el RGPD y potenciando el sitio web:

---

## 🔐 Seguridad

- `/.well-known/security.txt` implementado para divulgación responsable.
- Opcional: publicar clave PGP pública en `/pgp-key.txt`.

## 📈 Analítica Web (respetando privacidad)

- [Plausible](https://plausible.io/) – Analytics europeo, sin cookies ni rastreo.
- [Matomo](https://matomo.org/) – Alternativa self-hosted compatible con RGPD.
- Recomendación: añadir script desde `_layouts/default.html`.

## 💬 Comunicación directa

- [Formspree](https://formspree.io) – Formulario legal conectado.
- [Calendly](https://calendly.com) – Integración para reservas de consulta legal.
- Chatbots legales: integración opcional con Drift o Crisp AI bajo consentimiento.

## 🔍 SEO & Accesibilidad

- `jekyll-seo-tag` ya implementado.
- Añadir etiquetas Open Graph y Twitter Card personalizadas.
- Validar con [Lighthouse](https://pagespeed.web.dev/).

## 🗂 Documentación legal

- Añadir sección `transparencia.md` o `auditorias.md` con certificaciones y políticas.
- Visibilidad legal mejorada con `sitemap.xml` + `robots.txt`.

---

> Esta guía puede actualizarse en cada iteración del sitio y se recomienda como punto de partida para desplegar un stack legaltech ético y de confianza.