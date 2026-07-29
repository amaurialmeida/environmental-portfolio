# 🌿 Portafolio de Investigación Ambiental

**Amauri Almeida de Souza Junior**
`Gestión Ambiental` · `Ciencia de Datos` · `IA & Machine Learning`

> *"Datos para un planeta más verde"*

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-a8c5c0?style=flat-square&logo=googlechrome&logoColor=white)](https://amaurialmeida.github.io/environmental-portfolio)
[![GitHub](https://img.shields.io/badge/GitHub-amaurialmeida-2a3830?style=flat-square&logo=github)](https://github.com/amaurialmeida)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-amauri--almeida26-7ab3d4?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/amauri-almeida26/)
[![Status](https://img.shields.io/badge/Status-Active-4ade80?style=flat-square)]()

🌐 **Idiomas:** [English](README.md) | [Português](README.pt-BR.md) | Español | [Italiano](README.it.md)

---

## 📖 Descripción General

Este repositorio es el código fuente de mi **portafolio personal de investigación ambiental y ciencia de datos** — un sitio de una sola página, sin dependencias (HTML/CSS/JS puro, sin proceso de build) que reúne investigación de campo, dashboards y herramientas interactivas construidas durante trabajo de campo en **Brasil, Argentina y Chile**.

El sitio es nativamente **cuadrilingüe** (🇪🇸 ES · 🇬🇧 EN · 🇧🇷 PT · 🇮🇹 IT), con cambio instantáneo desde el encabezado — cada tarjeta de proyecto, publicación y widget interactivo está traducido, no solo el texto estático.

🔗 **Sitio en vivo:** [amaurialmeida.github.io/environmental-portfolio](https://amaurialmeida.github.io/environmental-portfolio)

---

## ✨ Funcionalidades

- **Globo 3D interactivo** (Globe.gl / Three.js) que muestra temperaturas mínimas/máximas reales de 2025 por país, con efectos de fuego, humo y contaminación sobre los indicadores en vivo.
- **Widget de datos ambientales en vivo** — indicadores en tiempo real (temperatura de glaciar, índice de calidad del aire, precipitación) obtenidos de Open-Meteo y WAQI, con caché y carga diferida.
- **Sistema de 4 idiomas** (ES/EN/PT/IT) que cubre toda la interfaz, incluyendo la calculadora y los widgets interactivos — no solo el texto estático.
- **Terminal de IA "Amauri Virtual"** — un widget conversacional basado en una API de inferencia gratuita, que responde preguntas de los visitantes sobre el portafolio.
- **Calculadora de huella ambiental de 10 preguntas**, con reacción en tiempo real del globo 3D, gráfico de distribución por categoría, comparación global y recomendaciones personalizadas.
- **Grafo de conocimiento interactivo** (D3.js force layout) que conecta todos los proyectos por tema, método y tecnología.
- **Dos páginas de estudio de caso a fondo** — inmersiones narrativas completas (problema, metodología, resultados, hallazgo inesperado, limitaciones, reflexión personal) más allá de lo que un dashboard por sí solo puede mostrar.
- **Changelog en vivo, actualizado automáticamente** en el pie de página, en los cuatro idiomas.

---

## 🗺️ Proyectos

| # | Proyecto | Región | Aspectos técnicos destacados |
|---|---|---|---|
| 01 | [Síndrome del Colapso de Colonias de Abejas](https://bee-colony-collapse-brazil.streamlit.app/) — [📖 estudio de caso](https://amaurialmeida.github.io/environmental-portfolio/case-study-abelhas.html) | Brasil (MG/SP/PR) | Python · Streamlit · Series temporales |
| 02 | [Observatorio del Río Santa Rita](https://santa-rita-river-observatory.streamlit.app/) — [📖 estudio de caso](https://amaurialmeida.github.io/environmental-portfolio/case-study-santa-rita.html) | Fernandópolis, SP | Python · Streamlit · Folium |
| 03 | [Monitoreo de Planta Solar — Noroeste de SP](https://solar-university-nw-sp.streamlit.app/) | São Paulo | Python · Streamlit · Plotly |
| 04 | [Potencial Eólico — Patagonia](https://patagonia-wind-energy.streamlit.app/) | Patagonia | Distribución de Weibull · ERA5/SENAMHI |
| 05 | [Calidad del Agua — Patagonia](https://patagonia-water-quality.streamlit.app/) | Patagonia (AR/CL) | Folium · Modelado de ICA |
| 06 | [Monitoreo Sísmico — Patagonia](https://patagonia-seismic.streamlit.app/) | Patagonia | API USGS · Gutenberg-Richter |
| 07 | [Impacto de Especies Exóticas Invasoras](https://invasive-alien-species-impact.streamlit.app/) | Puerto Williams, CL | Sentinel-2 · NDVI |
| 08 | [Observatorio de Abejas sin Aguijón](https://stingless-bee-observatory-br.streamlit.app/) | Brasil | Geoespacial · PRODES/INPE |
| 09 | [Pronóstico ML de El Niño 2026](https://el-nino-2026-ml-forecast.streamlit.app/) | Global | Random Forest · ENSO |
| 10 | [Road to Patagonia](https://road-to-patagonia.streamlit.app/) | BR · AR · CL | Autonomía de VE · mapeo de ruta |

Otras dos apps en vivo alimentan widgets del portafolio en lugar de ser tarjetas independientes: el [Carbon Footprint Tracker](https://carbon-footprint-tracker-tkfv5pthky3rk2gd8m9mm8.streamlit.app/) (versión completa de la calculadora integrada) y [Earth Min/Max Temperature History](https://earth-max-min-temp-history-4dwrafuhe7a5uhaqdkkzld.streamlit.app/) (fuente de datos del globo 3D).

Todas las apps de Streamlit se mantienen activas mediante un [flujo de keepalive en GitHub Actions basado en Playwright](https://github.com/amaurialmeida/streamlit-keepalive), evitando la hibernación del plan gratuito.

---

## 📖 Estudios de Caso a Fondo

Dos proyectos van más allá del dashboard con un relato narrativo completo — planteamiento del problema, metodología de campo, resultados reales, un hallazgo inesperado, limitaciones sin maquillaje y una reflexión personal sobre "qué haría diferente":

- **[Síndrome del Colapso de Colonias de Abejas](https://amaurialmeida.github.io/environmental-portfolio/case-study-abelhas.html)** — tesis de grado (FATEC Jundiaí, 2022), 4 apicultores, 338 colmenas, ~20M abejas.
- **[Observatorio del Río Santa Rita](https://amaurialmeida.github.io/environmental-portfolio/case-study-santa-rita.html)** — Iniciación Científica (UNICASTELO, 2015–2017), monitoreo de sedimentos en cuencas pareadas.

---

## 🎓 Formación Académica

| Programa | Institución |
|---|---|
| Técnico de Nivel Medio en Medio Ambiente | COTEC — Artes Labibe Faiad, Catalão, GO (2023) |
| Tecnólogo en Gestión Ambiental · 3er lugar ENADE | FATEC Jundiaí, SP |
| Tecnólogo · Análisis y Desarrollo de Sistemas | Facint, Maringá, PR |
| Posgrado · IA, Machine Learning & Data Science | Facint |
| Posgrado · Ciencia de Datos & Big Data Analytics | Facint |

---

## 💼 Experiencia Profesional

- **Analista de Soporte de Sistemas · TI** — ERP TOTVS · supervisión de planta solar de 1,07 GWh · gestión de residuos · estudio de disposición de residuos sólidos y compensación de carbono.
- **Pasante · Gestión Ambiental** — estudio de disposición de residuos sólidos en condominios residenciales y evaluación de compensación de carbono.

---

## 🛠️ Stack Tecnológico

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![Globe.gl](https://img.shields.io/badge/Globe.gl-7ab3d4?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

Sin proceso de build, sin bundler, sin framework — HTML/CSS/JS puro, servido directamente por GitHub Pages.

---

## 📁 Estructura del Repositorio

```
environmental-portfolio/
├── index.html                        # Portafolio principal (página única, ES/EN/PT/IT)
├── globe.html                        # Iframe del globo 3D (Globe.gl/Three.js)
├── greenlog.html                     # Frame de app en vivo integrado
├── case-study-abelhas.html           # Colapso de Abejas — estudio de caso completo
├── case-study-santa-rita.html        # Río Santa Rita — estudio de caso completo
├── README.md                         # Versión en inglés
├── README.pt-BR.md                   # Versión en portugués
├── README.es.md                      # Este archivo (español)
├── README.it.md                      # Versión en italiano
└── assets/
    ├── img/                          # Fotos, certificados, banderas, logo
    └── cv/                           # CVs descargables (EN/PT/ES)
```

---

## 🚀 Probar Localmente

```bash
# Clona el repositorio
git clone https://github.com/amaurialmeida/environmental-portfolio.git
cd environmental-portfolio

# Opción 1 — Python (sin instalación extra)
python -m http.server 8000
# Visita: http://localhost:8000

# Opción 2 — Node.js
npx serve .

# Opción 3 — Abrir directamente
# Arrastra index.html a Chrome o Firefox
```

---

## 🌐 Despliegue

| Plataforma | URL | Estado |
|---|---|---|
| GitHub Pages | `amaurialmeida.github.io/environmental-portfolio` | [![Pages](https://img.shields.io/badge/GitHub%20Pages-active-a8c5c0?style=flat-square)](https://amaurialmeida.github.io/environmental-portfolio) |
| Cloudflare Workers & Pages | `portfolio-ambiental.amauri-almeidasjr.workers.dev` | [![Workers](https://img.shields.io/badge/Cloudflare-active-F6821F?style=flat-square&logo=cloudflare&logoColor=white)](https://portfolio-ambiental.amauri-almeidasjr.workers.dev/) |

---

## 🔗 Enlaces Académicos / Profesionales

| Plataforma | Enlace |
|---|---|
| Lattes — Amauri A. de Souza Junior | http://lattes.cnpq.br/9545242042800090 |
| Escavador | https://www.escavador.com/sobre/8577779/amauri-almeida-de-souza-junior |
| LinkedIn | https://www.linkedin.com/in/amauri-almeida26/ |

---

© 2026 Amauri Almeida de Souza Junior · Portafolio de Investigación Ambiental
