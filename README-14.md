# 🌿 Environmental Research Portfolio

**Amauri Almeida de Souza Junior**
`Environmental Management` · `Data Science` · `AI & Machine Learning`

> *"Data for a greener planet"*

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-a8c5c0?style=flat-square&logo=googlechrome&logoColor=white)](https://amaurialmeida.github.io/environmental-portfolio)
[![GitHub](https://img.shields.io/badge/GitHub-amaurialmeida-2a3830?style=flat-square&logo=github)](https://github.com/amaurialmeida)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-amauri--almeida26-7ab3d4?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/amauri-almeida26/)
[![Status](https://img.shields.io/badge/Status-Active-4ade80?style=flat-square)]()

🌐 **Languages:** English | [Português](README.pt-BR.md) | [Español](README.es.md) | [Italiano](README.it.md)

---

## 📖 Overview

This repository is the source code for my personal **environmental research and data science portfolio** — a single-page, dependency-free site (plain HTML/CSS/JS, no build step) that brings together field research, dashboards, and interactive tools built over the course of fieldwork across **Brazil, Argentina, and Chile**.

The site is natively **quadrilingual** (🇬🇧 EN · 🇧🇷 PT · 🇪🇸 ES · 🇮🇹 IT), switchable instantly from the header — every project card, publication, and interactive widget is translated, not just the static text.

🔗 **Live site:** [amaurialmeida.github.io/environmental-portfolio](https://amaurialmeida.github.io/environmental-portfolio)

---

## ✨ Features

- **Interactive 3D globe** (Globe.gl / Three.js) rendering real-world 2025 min/max temperatures per country, with fire, smoke, and pollution effects layered on top of live indicators.
- **Live environmental data widget** — real-time indicators (glacier temperature, air quality index, precipitation) pulled from Open-Meteo and WAQI, cached and lazy-loaded.
- **4-language system** (EN/PT/ES/IT) covering the entire interface, including the calculator and interactive widgets — not just static copy.
- **"Amauri Virtual" AI terminal** — a conversational widget powered by a free inference API, answering visitor questions about the portfolio.
- **10-question environmental footprint calculator** with a real-time 3D globe reaction, category breakdown chart, global comparison, and personalized recommendations.
- **Interactive knowledge-graph** (D3.js force layout) connecting all projects by theme, method, and technology.
- **Two in-depth case study pages** — full narrative deep-dives (problem, methodology, results, unexpected findings, limitations, personal reflection) beyond what a dashboard alone can show.
- **Live, auto-updating changelog** in the footer, in all four languages.

---

## 🗺️ Projects

| # | Project | Region | Stack highlights |
|---|---|---|---|
| 01 | [Bee Colony Collapse Syndrome](https://bee-colony-collapse-brazil.streamlit.app/) — [📖 case study](https://amaurialmeida.github.io/environmental-portfolio/case-study-abelhas.html) | Brazil (MG/SP/PR) | Python · Streamlit · Time series |
| 02 | [Santa Rita River Observatory](https://santa-rita-river-observatory.streamlit.app/) — [📖 case study](https://amaurialmeida.github.io/environmental-portfolio/case-study-santa-rita.html) | Fernandópolis, SP | Python · Streamlit · Folium |
| 03 | [Solar Plant Monitoring — NW São Paulo](https://solar-university-nw-sp.streamlit.app/) | São Paulo | Python · Streamlit · Plotly |
| 04 | [Wind Energy Potential — Patagonia](https://patagonia-wind-energy.streamlit.app/) | Patagonia | Weibull analysis · ERA5/SENAMHI |
| 05 | [Water Quality — Patagonia](https://patagonia-water-quality.streamlit.app/) | Patagonia (AR/CL) | Folium · WQI modeling |
| 06 | [Seismic Monitoring — Patagonia](https://patagonia-seismic.streamlit.app/) | Patagonia | USGS API · Gutenberg-Richter |
| 07 | [Invasive Alien Species Impact](https://invasive-alien-species-impact.streamlit.app/) | Puerto Williams, CL | Sentinel-2 · NDVI |
| 08 | [Stingless Bee Observatory](https://stingless-bee-observatory-br.streamlit.app/) | Brazil | Geospatial · PRODES/INPE |
| 09 | [El Niño 2026 ML Forecast](https://el-nino-2026-ml-forecast.streamlit.app/) | Global | Random Forest · ENSO |
| 10 | [Road to Patagonia](https://road-to-patagonia.streamlit.app/) | BR · AR · CL | EV range · route mapping |

Two additional live apps power portfolio widgets rather than standing as standalone cards: the [Carbon Footprint Tracker](https://carbon-footprint-tracker-tkfv5pthky3rk2gd8m9mm8.streamlit.app/) (full version of the in-page calculator) and [Earth Min/Max Temperature History](https://earth-max-min-temp-history-4dwrafuhe7a5uhaqdkkzld.streamlit.app/) (data source for the 3D globe).

All Streamlit apps are kept awake by a [Playwright-based GitHub Actions keepalive workflow](https://github.com/amaurialmeida/streamlit-keepalive), preventing free-tier hibernation.

---

## 📖 In-Depth Case Studies

Two projects go beyond the dashboard with a full narrative write-up — problem framing, field methodology, real results, an unexpected finding, honest limitations, and a personal "what I'd do differently" reflection:

- **[Bee Colony Collapse Syndrome](https://amaurialmeida.github.io/environmental-portfolio/case-study-abelhas.html)** — undergraduate thesis (FATEC Jundiaí, 2022), 4 beekeepers, 338 hives, ~20M bees.
- **[Santa Rita River Observatory](https://amaurialmeida.github.io/environmental-portfolio/case-study-santa-rita.html)** — undergraduate research (UNICASTELO, 2015–2017), paired-basin sediment monitoring.

---

## 🎓 Academic Background

| Program | Institution |
|---|---|
| Technical High School Diploma in Environment | COTEC — Artes Labibe Faiad, Catalão, GO (2023) |
| Environmental Management Technologist · 3rd place ENADE | FATEC Jundiaí, SP |
| B.Tech · Systems Analysis and Development | Facint, Maringá, PR |
| Postgraduate · AI, Machine Learning & Data Science | Facint |
| Postgraduate · Data Science & Big Data Analytics | Facint |

---

## 💼 Professional Experience

- **Systems Support Analyst · IT** — TOTVS ERP · oversight of a 1.07 GWh solar plant · waste management · solid-waste disposal and carbon offset study.
- **Intern · Environmental Management** — solid-waste disposal study in residential condominiums and carbon offset assessment.

---

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![Globe.gl](https://img.shields.io/badge/Globe.gl-7ab3d4?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

No build step, no bundler, no framework — plain HTML/CSS/JS, served directly by GitHub Pages.

---

## 📁 Repository Structure

```
environmental-portfolio/
├── index.html                        # Main portfolio (single page, EN/PT/ES/IT)
├── globe.html                        # 3D globe iframe (Globe.gl/Three.js)
├── greenlog.html                     # Embedded live app frame
├── case-study-abelhas.html           # Bee Colony Collapse — full case study
├── case-study-santa-rita.html        # Santa Rita River — full case study
├── README.md                         # This file (English)
├── README.pt-BR.md                   # Portuguese version
├── README.es.md                      # Spanish version
├── README.it.md                      # Italian version
└── assets/
    ├── img/                          # Photos, certificates, flags, logo
    └── cv/                           # Downloadable CVs (EN/PT/ES)
```

---

## 🚀 Run Locally

```bash
# Clone the repository
git clone https://github.com/amaurialmeida/environmental-portfolio.git
cd environmental-portfolio

# Option 1 — Python (no extra install)
python -m http.server 8000
# Visit: http://localhost:8000

# Option 2 — Node.js
npx serve .

# Option 3 — Open directly
# Drag index.html into Chrome or Firefox
```

---

## 🌐 Deploy

| Platform | URL | Status |
|---|---|---|
| GitHub Pages | `amaurialmeida.github.io/environmental-portfolio` | [![Pages](https://img.shields.io/badge/GitHub%20Pages-active-a8c5c0?style=flat-square)](https://amaurialmeida.github.io/environmental-portfolio) |
| Cloudflare Workers & Pages | `portfolio-ambiental.amauri-almeidasjr.workers.dev` | [![Workers](https://img.shields.io/badge/Cloudflare-active-F6821F?style=flat-square&logo=cloudflare&logoColor=white)](https://portfolio-ambiental.amauri-almeidasjr.workers.dev/) |

---

## 🔗 Academic / Professional Links

| Platform | Link |
|---|---|
| Lattes — Amauri A. de Souza Junior | http://lattes.cnpq.br/9545242042800090 |
| Escavador | https://www.escavador.com/sobre/8577779/amauri-almeida-de-souza-junior |
| LinkedIn | https://www.linkedin.com/in/amauri-almeida26/ |

---

© 2026 Amauri Almeida de Souza Junior · Environmental Research Portfolio
