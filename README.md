# Portafolio de Análisis de Datos

Portafolio personal de proyectos de análisis de datos, desarrollados durante el curso de Análisis de Datos.

## Estructura del repositorio

```
/
├── index.html              ← Página principal del portafolio
├── projects/
│   └── lab-01.html         ← Lab 1.2.3 – Mercado laboral juvenil en CR
└── README.md
```

## Cómo publicar en GitHub Pages

### 1. Crear el repositorio en GitHub

```bash
# Desde la carpeta del portafolio
git init
git add .
git commit -m "feat: portafolio inicial con Lab 1.2.3"
```

### 2. Crear repositorio en GitHub

Ve a [github.com/new](https://github.com/new) y crea un repositorio.  
**Nombre recomendado:** `portafolio-datos` o `[tu-usuario].github.io`

> Si el repo se llama `[tu-usuario].github.io`, el sitio queda en `https://[tu-usuario].github.io`  
> Si tiene otro nombre, queda en `https://[tu-usuario].github.io/portafolio-datos`

### 3. Conectar y publicar

```bash
git remote add origin https://github.com/[tu-usuario]/[nombre-repo].git
git branch -M main
git push -u origin main
```

### 4. Activar GitHub Pages

1. Ve a **Settings** → **Pages**
2. En *Source*, selecciona **Deploy from a branch**
3. Elige la rama `main` y carpeta `/ (root)`
4. Guarda — en 1-2 minutos el sitio está en línea

## Proyectos

| # | Título | Estado | Fecha |
|---|--------|--------|-------|
| 01 | ¿Por qué es difícil el primer empleo en CR? | En desarrollo | Mayo 2026 |

## Tecnologías

- HTML puro + CSS custom properties
- Chart.js para visualizaciones
- Google Fonts (DM Serif Display, DM Mono, DM Sans)
- Sin dependencias de build — se publica directamente

---

*Actualizado: Mayo 2026*
