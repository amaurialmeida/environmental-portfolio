# 🌿 Portfolio di Ricerca Ambientale

**Amauri Almeida de Souza Junior**
`Gestione Ambientale` · `Data Science` · `IA & Machine Learning`

> *"Dati per un pianeta più verde"*

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-a8c5c0?style=flat-square&logo=googlechrome&logoColor=white)](https://amaurialmeida.github.io/environmental-portfolio)
[![GitHub](https://img.shields.io/badge/GitHub-amaurialmeida-2a3830?style=flat-square&logo=github)](https://github.com/amaurialmeida)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-amauri--almeida26-7ab3d4?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/amauri-almeida26/)
[![Status](https://img.shields.io/badge/Status-Active-4ade80?style=flat-square)]()

🌐 **Lingue:** [English](README.md) | [Português](README.pt-BR.md) | [Español](README.es.md) | Italiano

---

## 📖 Panoramica

Questo repository è il codice sorgente del mio **portfolio personale di ricerca ambientale e data science** — un sito a pagina unica, senza dipendenze (HTML/CSS/JS puro, senza processo di build) che riunisce ricerca sul campo, dashboard e strumenti interattivi costruiti durante il lavoro sul campo in **Brasile, Argentina e Cile**.

Il sito è nativamente **quadrilingue** (🇮🇹 IT · 🇬🇧 EN · 🇧🇷 PT · 🇪🇸 ES), con cambio istantaneo dall'intestazione — ogni card di progetto, pubblicazione e widget interattivo è tradotto, non solo il testo statico.

🔗 **Sito live:** [amaurialmeida.github.io/environmental-portfolio](https://amaurialmeida.github.io/environmental-portfolio)

---

## ✨ Funzionalità

- **Globo 3D interattivo** (Globe.gl / Three.js) che mostra le temperature minime/massime reali del 2025 per paese, con effetti di fuoco, fumo e inquinamento sovrapposti agli indicatori in tempo reale.
- **Widget di dati ambientali in tempo reale** — indicatori live (temperatura del ghiacciaio, indice di qualità dell'aria, precipitazioni) provenienti da Open-Meteo e WAQI, con cache e caricamento differito.
- **Sistema a 4 lingue** (IT/EN/PT/ES) che copre l'intera interfaccia, inclusa la calcolatrice e i widget interattivi — non solo il testo statico.
- **Terminale IA "Amauri Virtual"** — un widget conversazionale basato su un'API di inferenza gratuita, che risponde alle domande dei visitatori sul portfolio.
- **Calcolatrice dell'impronta ambientale a 10 domande**, con reazione in tempo reale del globo 3D, grafico di distribuzione per categoria, confronto globale e raccomandazioni personalizzate.
- **Grafo di conoscenza interattivo** (D3.js force layout) che collega tutti i progetti per tema, metodo e tecnologia.
- **Due pagine di studio di caso approfondito** — analisi narrative complete (problema, metodologia, risultati, scoperta inaspettata, limiti, riflessione personale) oltre a ciò che una dashboard da sola può mostrare.
- **Changelog live, aggiornato automaticamente** nel footer, in tutte e quattro le lingue.

---

## 🗺️ Progetti

| # | Progetto | Regione | Punti tecnici salienti |
|---|---|---|---|
| 01 | [Sindrome del Collasso delle Colonie di Api](https://bee-colony-collapse-brazil.streamlit.app/) — [📖 studio di caso](https://amaurialmeida.github.io/environmental-portfolio/case-study-abelhas.html) | Brasile (MG/SP/PR) | Python · Streamlit · Serie temporali |
| 02 | [Osservatorio del Fiume Santa Rita](https://santa-rita-river-observatory.streamlit.app/) — [📖 studio di caso](https://amaurialmeida.github.io/environmental-portfolio/case-study-santa-rita.html) | Fernandópolis, SP | Python · Streamlit · Folium |
| 03 | [Monitoraggio Impianto Solare — Nord-Ovest di SP](https://solar-university-nw-sp.streamlit.app/) | San Paolo | Python · Streamlit · Plotly |
| 04 | [Potenziale Eolico — Patagonia](https://patagonia-wind-energy.streamlit.app/) | Patagonia | Distribuzione di Weibull · ERA5/SENAMHI |
| 05 | [Qualità dell'Acqua — Patagonia](https://patagonia-water-quality.streamlit.app/) | Patagonia (AR/CL) | Folium · Modellazione IQA |
| 06 | [Monitoraggio Sismico — Patagonia](https://patagonia-seismic.streamlit.app/) | Patagonia | API USGS · Gutenberg-Richter |
| 07 | [Impatto delle Specie Esotiche Invasive](https://invasive-alien-species-impact.streamlit.app/) | Puerto Williams, CL | Sentinel-2 · NDVI |
| 08 | [Osservatorio delle Api senza Pungiglione](https://stingless-bee-observatory-br.streamlit.app/) | Brasile | Geospaziale · PRODES/INPE |
| 09 | [Previsione ML del El Niño 2026](https://el-nino-2026-ml-forecast.streamlit.app/) | Globale | Random Forest · ENSO |
| 10 | [Road to Patagonia](https://road-to-patagonia.streamlit.app/) | BR · AR · CL | Autonomia EV · mappatura del percorso |

Altre due app live alimentano i widget del portfolio invece di essere card indipendenti: il [Carbon Footprint Tracker](https://carbon-footprint-tracker-tkfv5pthky3rk2gd8m9mm8.streamlit.app/) (versione completa della calcolatrice integrata) ed [Earth Min/Max Temperature History](https://earth-max-min-temp-history-4dwrafuhe7a5uhaqdkkzld.streamlit.app/) (fonte dati del globo 3D).

Tutte le app Streamlit vengono mantenute attive da un [workflow di keepalive su GitHub Actions basato su Playwright](https://github.com/amaurialmeida/streamlit-keepalive), evitando l'ibernazione del piano gratuito.

---

## 📖 Studi di Caso Approfonditi

Due progetti vanno oltre la dashboard con un resoconto narrativo completo — inquadramento del problema, metodologia di campo, risultati reali, una scoperta inaspettata, limiti onesti e una riflessione personale su "cosa farei diversamente":

- **[Sindrome del Collasso delle Colonie di Api](https://amaurialmeida.github.io/environmental-portfolio/case-study-abelhas.html)** — tesi di laurea (FATEC Jundiaí, 2022), 4 apicoltori, 338 alveari, ~20M di api.
- **[Osservatorio del Fiume Santa Rita](https://amaurialmeida.github.io/environmental-portfolio/case-study-santa-rita.html)** — ricerca undergraduate (UNICASTELO, 2015–2017), monitoraggio dei sedimenti in bacini appaiati.

---

## 🎓 Formazione Accademica

| Corso | Istituzione |
|---|---|
| Diploma Tecnico in Ambiente | COTEC — Artes Labibe Faiad, Catalão, GO (2023) |
| Tecnologo in Gestione Ambientale · 3° posto ENADE | FATEC Jundiaí, SP |
| Laurea Tecnica · Analisi e Sviluppo di Sistemi | Facint, Maringá, PR |
| Specializzazione · IA, Machine Learning & Data Science | Facint |
| Specializzazione · Data Science & Big Data Analytics | Facint |

---

## 💼 Esperienza Professionale

- **Analista di Supporto Sistemi · IT** — ERP TOTVS · supervisione di un impianto solare da 1,07 GWh · gestione dei rifiuti · studio sullo smaltimento dei rifiuti solidi e compensazione del carbonio.
- **Stage · Gestione Ambientale** — studio sullo smaltimento dei rifiuti solidi nei condomini e valutazione della compensazione del carbonio.

---

## 🛠️ Stack Tecnologico

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![Globe.gl](https://img.shields.io/badge/Globe.gl-7ab3d4?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

Nessun processo di build, nessun bundler, nessun framework — HTML/CSS/JS puro, servito direttamente da GitHub Pages.

---

## 📁 Struttura del Repository

```
environmental-portfolio/
├── index.html                        # Portfolio principale (pagina unica, IT/EN/PT/ES)
├── globe.html                        # Iframe del globo 3D (Globe.gl/Three.js)
├── greenlog.html                     # Frame dell'app live integrata
├── case-study-abelhas.html           # Collasso delle Api — studio di caso completo
├── case-study-santa-rita.html        # Fiume Santa Rita — studio di caso completo
├── README.md                         # Versione inglese
├── README.pt-BR.md                   # Versione portoghese
├── README.es.md                      # Versione spagnola
├── README.it.md                      # Questo file (italiano)
└── assets/
    ├── img/                          # Foto, certificati, bandiere, logo
    └── cv/                           # CV scaricabili (EN/PT/ES)
```

---

## 🚀 Esecuzione Locale

```bash
# Clona il repository
git clone https://github.com/amaurialmeida/environmental-portfolio.git
cd environmental-portfolio

# Opzione 1 — Python (nessuna installazione extra)
python -m http.server 8000
# Visita: http://localhost:8000

# Opzione 2 — Node.js
npx serve .

# Opzione 3 — Apri direttamente
# Trascina index.html su Chrome o Firefox
```

---

## 🌐 Deploy

| Piattaforma | URL | Stato |
|---|---|---|
| GitHub Pages | `amaurialmeida.github.io/environmental-portfolio` | [![Pages](https://img.shields.io/badge/GitHub%20Pages-active-a8c5c0?style=flat-square)](https://amaurialmeida.github.io/environmental-portfolio) |
| Cloudflare Workers & Pages | `portfolio-ambiental.amauri-almeidasjr.workers.dev` | [![Workers](https://img.shields.io/badge/Cloudflare-active-F6821F?style=flat-square&logo=cloudflare&logoColor=white)](https://portfolio-ambiental.amauri-almeidasjr.workers.dev/) |

---

## 🔗 Link Accademici / Professionali

| Piattaforma | Link |
|---|---|
| Lattes — Amauri A. de Souza Junior | http://lattes.cnpq.br/9545242042800090 |
| Escavador | https://www.escavador.com/sobre/8577779/amauri-almeida-de-souza-junior |
| LinkedIn | https://www.linkedin.com/in/amauri-almeida26/ |

---

© 2026 Amauri Almeida de Souza Junior · Portfolio di Ricerca Ambientale
