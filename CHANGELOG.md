# CHANGELOG.md — Release v1.0.0

**Proyecto:** GORTAZAR Legal Advisors – Web Corporativa Jekyll  
**Fecha:** 2025-04-03  
**Rama:** `release/jekyll-final-with-workflow`  
**Versión:** `v1.0.0`  
**Despliegue:** GitHub Pages desde carpeta `/docs`  
**SDLC Etapa:** Release Candidate – Ready for Production

---

## ✨ Novedades y funcionalidades

### 🌐 Web multilingüe 100% funcional (`es`, `en`, `pt`, `it`)
- Rutas independientes por idioma
- Navegación y contenido sincronizado en todos los idiomas
- Selector de idioma con redirección dinámica y mobile-first

### 🎨 Diseño corporativo aplicado (branding compliance)
- Header visual con logo (`logo_gortazar.png`)
- Membrete superior (`membrete_landing.png`)
- Banner institucional inferior (`footer_visual_banner.png`)
- Firma visual con RGPD (`firma_email_detallada.png`)
- Tipografía profesional, paleta corporativa sobria: `azul marino`, `gris`, `blanco`

### 🧭 UX/UI Responsive y Moderno
- Navegación accesible desde móviles y tablets
- Layout centrado, márgenes amplios, animaciones suaves
- HTML/CSS nativo puro sin frameworks externos

### 📬 Página de contacto con integración legal
- Formulario conectado a Formspree (cumpliendo RGPD)
- Firma visual + pie legal de contacto
- Página traducida en todos los idiomas

---

## 🛡️ Compliance & Seguridad

- `security.txt` en `.well-known/`
- Metadatos OpenGraph y SEO tags (`og:title`, `og:image`, `description`, etc.)
- Enlaces accesibles para política de privacidad y términos
- Títulos dinámicos por página y metadatos accesibles por idioma

---

## ⚙️ Workflows CI/CD integrados

- GitHub Pages desde `/docs` configurado
- Workflow `post-deploy.yml` para validación manual:
  - Validación HTML con `tidy`
  - Test de carga de recursos visuales (`curl`)
  - Detección de formulario en contacto
- **No incluye `deploy.yml` redundante** (Pages usa el build integrado oficial)

---

## 📁 Estructura del proyecto

```
/docs/
├── index.html
├── es/, en/, pt/, it/
├── _layouts/
├── _data/navigation.yml
├── assets/images/
├── assets/css/custom.css
├── .well-known/security.txt
_config.yml

/.github/workflows/
└── post-deploy.yml
```

---

## 🧪 Validación QA (UAT)

✅ Validado con checklist completo (branding, accesibilidad, idiomas, formularios)  
✅ Testeado visualmente en navegadores modernos  
✅ Compatible con navegadores móviles/tablets  
✅ Preparado para merge en `main` y despliegue continuo

---

## 🔖 Tags sugeridos para el release

```
Tag:            v1.0.0
Release name:   Public Website Launch – Multilingual & Legal Branding
Target branch:  main
```