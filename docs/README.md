# 🧭 GORTAZAR Legal Advisors · GitHub Pages (modo Jekyll Pro)

¡Bienvenido/a al **sitio oficial** de GORTAZAR Legal Advisors, potenciado por GitHub Pages y Jekyll!

---

## 🎯 Objetivo del juego

🚀 Desplegar una landing page profesional y moderna para nuestro bufete legal, **en menos de 5 minutos**.

---

## 🧩 Nivel 1: Clona el repositorio

```bash
git clone https://github.com/gortazar-legaltech/gortazar-legaltech.git
cd gortazar-legaltech
```

🗂 Asegúrate de que todo el contenido esté dentro de la carpeta `/docs/`.

---

## 🔧 Nivel 2: Activa GitHub Pages

Ve a `Settings → Pages` y configura:

- **Source**: Deploy from a branch
- **Branch**: `main`
- **Folder**: `/docs`

Haz clic en ✅ **Save** y desbloquea la siguiente fase.

---

## 🤖 Nivel 3: CI/CD Automágico

Este repositorio incluye:

- `.github/workflows/deploy.yml` → ¡tu lanzador automático!
- `Gemfile` + `Gemfile.lock` → dependencias para Jekyll
- Tema `just-the-docs` personalizado con **modo oscuro**, navegación superior y SEO optimizado

---

## 📁 Estructura del proyecto

```
📁 docs/
├── index.md
├── about.md
├── privacidad.md
├── _layouts/
│   └── default.html
├── assets/
│   ├── images/
│   │   ├── logo_gortazar.svg
│   │   └── favicon.ico
│   └── css/
│       └── custom.css
├── .github/
│   └── workflows/
│       └── deploy.yml
├── Gemfile
└── Gemfile.lock
```

---

## 🧙‍♂️ Bonus: Personaliza tu hechizo

- Edita `index.md` para cambiar el mensaje principal
- Agrega páginas `.md` para nuevos servicios
- Personaliza colores y fuentes desde `custom.css`

---

## 🧠 Recompensa Final

Cuando completes todos los pasos y actualices tu `main`, GitHub desplegará tu web en:

👉 **https://gortazar-legaltech.github.io/gortazar-legaltech/**

---

## 🙌 Créditos

Diseño e implementación por **GORTAZAR Legal Advisors** con visión Atlántica y LegalTech.

> “Navegando la Justicia con Sabiduría Ancestral”