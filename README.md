# 📊 Portafolio de Ciencia de Datos — Luis Steven Madriz Campos

> Portafolio de análisis y ciencia de datos desarrollado en el marco del programa de formación del **MICITT** (Ministerio de Ciencia, Innovación, Tecnología y Telecomunicaciones de Costa Rica) con **Cisco Networking Academy**, complementado con proyectos personales de exploración de datos aplicados al contexto costarricense.

🔗 **Demo en vivo:** [mochi00001.github.io/Portafolio-Labs-Ciencia-de-Datos-MICITT](https://mochi00001.github.io/Portafolio-Labs-Ciencia-de-Datos-MICITT/)

---

## 📋 Índice

- [Sobre este portafolio](#-sobre-este-portafolio)
- [Formación completada](#-formación-completada)
- [Proyectos](#-proyectos)
- [Laboratorios](#-laboratorios)
- [Estructura del repositorio](#-estructura-del-repositorio)
- [Tecnologías](#-tecnologías)
- [Enfoque metodológico](#-enfoque-metodológico)
- [Estado del portafolio](#-estado-del-portafolio)
- [Sobre mí](#-sobre-mí)
- [Créditos](#-créditos)

---

## 🎯 Sobre este portafolio

Documenta mi proceso de aprendizaje y práctica en análisis y ciencia de datos: los laboratorios de dos cursos de Cisco Networking Academy / MICITT, reescritos como *writeups* con el diseño editorial del portafolio, más proyectos de investigación propios sobre problemáticas costarricenses.

**Objetivo:** demostrar competencias en el ciclo completo de análisis de datos —de la pregunta de negocio a la comunicación de resultados— como estudiante avanzado de la Licenciatura en **Administración de Tecnologías de Información (ATI)** del TEC.

---

## 🎓 Formación completada

| Curso | Módulos | Estado | Certificado |
|---|---|---|---|
| **Data Analytics Essentials** (Aspectos básicos del análisis de datos) | 9 | ✅ Completado · 2026 | [PDF](./fundamentos-ciencia-datos/certificado/data-analytics-essentials-cert.pdf) |
| **Introduction to Data Science** (Introducción a la Ciencia de Datos) | 4 | ✅ Completado · 2026 | [PDF](./intro-ciencia-datos/certificado/intro-data-science-cert.pdf) |

**Data Analytics Essentials** — ciclo de vida del análisis; transformación, estadística y visualización con Excel; consultas SQL a bases de datos relacionales; visualización con Tableau; ética y sesgo en los datos. → [Página del curso](./fundamentos-ciencia-datos/index.html)

**Introduction to Data Science** — qué son los datos y cómo nos rodean; recopilación y almacenamiento de datos masivos; inteligencia artificial y aprendizaje automático; el camino profesional en analítica. → [Página del curso](./intro-ciencia-datos/index.html)

---

## 🗂️ Proyectos

| # | Título | Descripción | Herramientas | Estado |
|---|--------|-------------|--------------|--------|
| 01 | [¿Por qué es tan difícil conseguir el primer empleo en Costa Rica?](./fundamentos-ciencia-datos/modulo-01/lab-01.html) | Análisis descriptivo del desempleo juvenil: factores estructurales, comparación con Latinoamérica y la OCDE | HTML, Chart.js, datos INEC · OCDE · OIT | 🔄 En desarrollo |
| 02 | Capstone — análisis del dataset de películas | Éxito comercial vs. calificación vs. año de estreno, sobre 50 años de cine | Excel · SQL · Tableau | 📅 Planificado |

---

## 🧪 Laboratorios

Cada laboratorio de NetAcad está reescrito como un *writeup* (qué se practicó, consultas y hallazgos). El export original de la plataforma queda enlazado en `labs/originales/`.

### Data Analytics Essentials — SQL

| Lab | Conceptos |
|---|---|
| [SQL en el mundo](./fundamentos-ciencia-datos/labs/lab-sql-en-el-mundo.html) | `SELECT`, comodín `*`, `WHERE`, `AND` / `OR` |
| [Ordenación y limitación](./fundamentos-ciencia-datos/labs/lab-ordenacion-y-limitacion.html) | `ORDER BY`, `DESC` / `ASC`, `LIMIT` |
| [Agrupación de datos](./fundamentos-ciencia-datos/labs/lab-agrupacion-de-datos.html) | `GROUP BY` |
| [Columnas calculadas](./fundamentos-ciencia-datos/labs/lab-columnas-calculadas.html) | `SUM`, `COUNT`, `AVG`, `AS`, `DISTINCT` |
| [Unión de tablas](./fundamentos-ciencia-datos/labs/lab-union-de-tablas.html) | `NATURAL JOIN`, `JOIN … ON`, `CROSS JOIN` |
| [Películas exitosas](./fundamentos-ciencia-datos/labs/lab-peliculas-exitosas.html) | Ranking, rentabilidad (`revenue < budget`) — dataset del capstone |

### Introduction to Data Science — tablas dinámicas e IA

| Lab | Conceptos |
|---|---|
| [Pivotar = agrupar](./intro-ciencia-datos/labs/lab-pivotar-agrupar.html) | Primera tabla dinámica: organizar y contar |
| [Gráficos dinámicos](./intro-ciencia-datos/labs/lab-graficos-dinamicos.html) | Resumir con `count` / `avg` / `sum` |
| [Heladería](./intro-ciencia-datos/labs/lab-heladeria.html) | EDA completo: filas, columnas, filtros, segmentación |
| [Explorar CopyAI](./intro-ciencia-datos/labs/lab-explorar-copyai.html) | Herramientas de IA generativa, modelo de acceso y límites |

---

## 📁 Estructura del repositorio

```
.
├── index.html                      Landing del portafolio
├── assets/portfolio.css            Sistema de diseño compartido
├── fundamentos-ciencia-datos/      Data Analytics Essentials
│   ├── index.html                  Página del curso
│   ├── modulo-01/                  Lab 01 + investigación de portafolios
│   ├── modulo-02/ modulo-03/       Resúmenes de estudio y datasets de bicicletas
│   ├── labs/                       Writeups + originales/ (exports de NetAcad)
│   ├── datos/                      Movies_data_2000.xlsx, Bigfoot.csv
│   └── certificado/
└── intro-ciencia-datos/            Introduction to Data Science
    ├── index.html                  Página del curso
    ├── labs/                       Writeups + originales/
    └── certificado/
```

---

## 🛠️ Tecnologías

- **SQL** — `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`, funciones de agregación, `JOIN`
- **Microsoft Excel** — fórmulas y funciones, importación de CSV, tablas dinámicas, columnas calculadas
- **Tableau** — visualizaciones y paneles
- **Python** — pandas / matplotlib (en aprendizaje activo, para los proyectos)
- **Chart.js** — visualizaciones interactivas en la web
- **HTML + CSS** — portafolio estático sin build; **GitHub Pages**; **Git / GitHub**

---

## 🔄 Enfoque metodológico

Todos los proyectos siguen el **ciclo de vida del análisis de datos**:

```
1. Comprensión del negocio   → definir problema, objetivos y métricas
2. Comprensión de los datos  → identificar fuentes, explorar, evaluar calidad
3. Preparación de datos       → limpieza, transformación, integración
4. Análisis / modelado        → estadística y visualización
5. Evaluación                 → validar contra los objetivos
6. Comunicación               → hallazgos claros y accionables
```

---

## 📌 Estado del portafolio

| Componente | Estado |
|-----------|--------|
| Data Analytics Essentials — curso y 6 labs | ✅ Completo |
| Introduction to Data Science — curso y 4 labs | ✅ Completo |
| Landing y páginas de curso rediseñadas | ✅ Completo |
| Proyecto 01 — desempleo juvenil CR | 🔄 En desarrollo |
| Proyecto 02 — capstone de películas | 📅 Planificado |
| Primer artículo en Medium | 📅 Planificado |

**Versión actual:** v1.0 — *dos cursos completados e integrados*

---

## 👤 Sobre mí

**Luis Steven Madriz Campos** · 📍 Cartago, Costa Rica · 📧 luismadriz9@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/luismadriz13/) · [GitHub](https://github.com/mochi00001) · [Medium](https://medium.com/@luismadriz9)

Estudiante de Licenciatura en **Administración de Tecnologías de Información (ATI)** en el Instituto Tecnológico de Costa Rica (TEC), semestre 7 de 10. Mi perfil combina gestión de proyectos, sistemas de información y análisis de negocio; este portafolio añade la capa de datos que completa la visión del **puente entre negocio y tecnología**.

---

## 🙏 Créditos

- **MICITT** y **Cisco Networking Academy** — programa de formación en ciencia de datos
- **Instituto Tecnológico de Costa Rica (TEC)** — formación base en ATI
- **Chart.js** — biblioteca de visualización open source
- **INEC**, **OCDE**, **OIT** — datos abiertos para el Proyecto 01

---

*📅 Actualizado: setiembre 2026 · Luis Steven Madriz Campos*
