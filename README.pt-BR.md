# 🌿 Portfólio de Pesquisa Ambiental

**Amauri Almeida de Souza Junior**
`Gestão Ambiental` · `Ciência de Dados` · `IA & Machine Learning`

> *"Dados para um planeta mais verde"*

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-a8c5c0?style=flat-square&logo=googlechrome&logoColor=white)](https://amaurialmeida.github.io/environmental-portfolio)
[![GitHub](https://img.shields.io/badge/GitHub-amaurialmeida-2a3830?style=flat-square&logo=github)](https://github.com/amaurialmeida)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-amauri--almeida26-7ab3d4?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/amauri-almeida26/)
[![Status](https://img.shields.io/badge/Status-Active-4ade80?style=flat-square)]()

🌐 **Idiomas:** [English](README.md) | Português | [Español](README.es.md) | [Italiano](README.it.md)

---

## 📖 Visão Geral

Este repositório é o código-fonte do meu **portfólio pessoal de pesquisa ambiental e ciência de dados** — um site de página única, sem dependências (HTML/CSS/JS puro, sem etapa de build) que reúne pesquisa de campo, dashboards e ferramentas interativas construídas ao longo de trabalho de campo no **Brasil, Argentina e Chile**.

O site é nativamente **quadrilíngue** (🇧🇷 PT · 🇬🇧 EN · 🇪🇸 ES · 🇮🇹 IT), com troca instantânea pelo cabeçalho — cada card de projeto, publicação e widget interativo é traduzido, não só o texto estático.

🔗 **Site ao vivo:** [amaurialmeida.github.io/environmental-portfolio](https://amaurialmeida.github.io/environmental-portfolio)

---

## ✨ Funcionalidades

- **Globo 3D interativo** (Globe.gl / Three.js) exibindo temperaturas mínimas/máximas reais de 2025 por país, com efeitos de fogo, fumaça e poluição sobrepostos aos indicadores ao vivo.
- **Widget de dados ambientais ao vivo** — indicadores em tempo real (temperatura de geleira, índice de qualidade do ar, precipitação) vindos do Open-Meteo e WAQI, com cache e carregamento preguiçoso.
- **Sistema de 4 idiomas** (PT/EN/ES/IT) cobrindo toda a interface, incluindo a calculadora e os widgets interativos — não só o texto estático.
- **Terminal de IA "Amauri Virtual"** — um widget conversacional alimentado por uma API de inferência gratuita, respondendo perguntas de visitantes sobre o portfólio.
- **Calculadora de pegada ambiental com 10 perguntas**, com reação em tempo real do globo 3D, gráfico de distribuição por categoria, comparação global e recomendações personalizadas.
- **Grafo de conhecimento interativo** (D3.js force layout) conectando todos os projetos por tema, método e tecnologia.
- **Duas páginas de estudo de caso aprofundado** — mergulhos narrativos completos (problema, metodologia, resultados, achado inesperado, limitações, reflexão pessoal) além do que um dashboard sozinho consegue mostrar.
- **Changelog ao vivo, atualizado automaticamente** no rodapé, nos quatro idiomas.

---

## 🗺️ Projetos

| # | Projeto | Região | Destaques técnicos |
|---|---|---|---|
| 01 | [Síndrome do Colapso das Colônias de Abelhas](https://bee-colony-collapse-brazil.streamlit.app/) — [📖 estudo de caso](https://amaurialmeida.github.io/environmental-portfolio/case-study-abelhas.html) | Brasil (MG/SP/PR) | Python · Streamlit · Séries temporais |
| 02 | [Observatório do Rio Santa Rita](https://santa-rita-river-observatory.streamlit.app/) — [📖 estudo de caso](https://amaurialmeida.github.io/environmental-portfolio/case-study-santa-rita.html) | Fernandópolis, SP | Python · Streamlit · Folium |
| 03 | [Monitoramento da Usina Solar — Noroeste de SP](https://solar-university-nw-sp.streamlit.app/) | São Paulo | Python · Streamlit · Plotly |
| 04 | [Potencial Eólico — Patagônia](https://patagonia-wind-energy.streamlit.app/) | Patagônia | Distribuição de Weibull · ERA5/SENAMHI |
| 05 | [Qualidade da Água — Patagônia](https://patagonia-water-quality.streamlit.app/) | Patagônia (AR/CL) | Folium · Modelagem de IQA |
| 06 | [Monitoramento Sísmico — Patagônia](https://patagonia-seismic.streamlit.app/) | Patagônia | API USGS · Gutenberg-Richter |
| 07 | [Impacto de Espécies Exóticas Invasoras](https://invasive-alien-species-impact.streamlit.app/) | Puerto Williams, CL | Sentinel-2 · NDVI |
| 08 | [Observatório de Abelhas sem Ferrão](https://stingless-bee-observatory-br.streamlit.app/) | Brasil | Geoespacial · PRODES/INPE |
| 09 | [Previsão ML do El Niño 2026](https://el-nino-2026-ml-forecast.streamlit.app/) | Global | Random Forest · ENSO |
| 10 | [Road to Patagonia](https://road-to-patagonia.streamlit.app/) | BR · AR · CL | Autonomia de VE · mapeamento de rota |

Dois outros apps ao vivo alimentam widgets do portfólio em vez de serem cards independentes: o [Carbon Footprint Tracker](https://carbon-footprint-tracker-tkfv5pthky3rk2gd8m9mm8.streamlit.app/) (versão completa da calculadora embutida) e o [Earth Min/Max Temperature History](https://earth-max-min-temp-history-4dwrafuhe7a5uhaqdkkzld.streamlit.app/) (fonte de dados do globo 3D).

Todos os apps Streamlit são mantidos ativos por um [workflow de keepalive no GitHub Actions baseado em Playwright](https://github.com/amaurialmeida/streamlit-keepalive), evitando a hibernação do plano gratuito.

---

## 📖 Estudos de Caso Aprofundados

Dois projetos vão além do dashboard com um relato narrativo completo — definição do problema, metodologia de campo, resultados reais, um achado inesperado, limitações sem maquiagem e uma reflexão pessoal sobre "o que eu faria diferente":

- **[Síndrome do Colapso das Colônias de Abelhas](https://amaurialmeida.github.io/environmental-portfolio/case-study-abelhas.html)** — TCC (FATEC Jundiaí, 2022), 4 apicultores, 338 colmeias, ~20M abelhas.
- **[Observatório do Rio Santa Rita](https://amaurialmeida.github.io/environmental-portfolio/case-study-santa-rita.html)** — Iniciação Científica (UNICASTELO, 2015–2017), monitoramento de sedimentos em bacias pareadas.

---

## 🎓 Formação Acadêmica

| Curso | Instituição |
|---|---|
| Técnico de Nível Médio em Meio Ambiente | COTEC — Artes Labibe Faiad, Catalão, GO (2023) |
| Tecnólogo em Gestão Ambiental · 3º lugar ENADE | FATEC Jundiaí, SP |
| Tecnólogo · Análise e Desenvolvimento de Sistemas | Facint, Maringá, PR |
| Pós-graduação · IA, Machine Learning & Data Science | Facint |
| Pós-graduação · Ciência de Dados & Big Data Analytics | Facint |

---

## 💼 Experiência Profissional

- **Analista de Suporte de Sistemas · TI** — ERP TOTVS · supervisão de usina solar de 1,07 GWh · gestão de resíduos · estudo de descarte de resíduos sólidos e compensação de carbono.
- **Estagiário · Gestão Ambiental** — estudo de descarte de resíduos sólidos em condomínios residenciais e avaliação de compensação de carbono.

---

## 🛠️ Stack Tecnológico

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![Globe.gl](https://img.shields.io/badge/Globe.gl-7ab3d4?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

Sem etapa de build, sem bundler, sem framework — HTML/CSS/JS puro, servido diretamente pelo GitHub Pages.

---

## 📁 Estrutura do Repositório

```
environmental-portfolio/
├── index.html                        # Portfólio principal (página única, PT/EN/ES/IT)
├── globe.html                        # Iframe do globo 3D (Globe.gl/Three.js)
├── greenlog.html                     # Frame de app ao vivo embutido
├── case-study-abelhas.html           # Colapso das Abelhas — estudo de caso completo
├── case-study-santa-rita.html        # Rio Santa Rita — estudo de caso completo
├── README.md                         # Versão em inglês
├── README.pt-BR.md                   # Este arquivo (português)
├── README.es.md                      # Versão em espanhol
├── README.it.md                      # Versão em italiano
└── assets/
    ├── img/                          # Fotos, certificados, bandeiras, logo
    └── cv/                           # Currículos para download (EN/PT/ES)
```

---

## 🚀 Como Testar Localmente

```bash
# Clone o repositório
git clone https://github.com/amaurialmeida/environmental-portfolio.git
cd environmental-portfolio

# Opção 1 — Python (sem instalação extra)
python -m http.server 8000
# Acesse: http://localhost:8000

# Opção 2 — Node.js
npx serve .

# Opção 3 — Abrir direto
# Arraste o index.html para o Chrome ou Firefox
```

---

## 🌐 Deploy

| Plataforma | URL | Status |
|---|---|---|
| GitHub Pages | `amaurialmeida.github.io/environmental-portfolio` | [![Pages](https://img.shields.io/badge/GitHub%20Pages-active-a8c5c0?style=flat-square)](https://amaurialmeida.github.io/environmental-portfolio) |
| Cloudflare Workers & Pages | `portfolio-ambiental.amauri-almeidasjr.workers.dev` | [![Workers](https://img.shields.io/badge/Cloudflare-active-F6821F?style=flat-square&logo=cloudflare&logoColor=white)](https://portfolio-ambiental.amauri-almeidasjr.workers.dev/) |

---

## 🔗 Links Acadêmicos / Profissionais

| Plataforma | Link |
|---|---|
| Lattes — Amauri A. de Souza Junior | http://lattes.cnpq.br/9545242042800090 |
| Escavador | https://www.escavador.com/sobre/8577779/amauri-almeida-de-souza-junior |
| LinkedIn | https://www.linkedin.com/in/amauri-almeida26/ |

---

© 2026 Amauri Almeida de Souza Junior · Portfólio de Pesquisa Ambiental
