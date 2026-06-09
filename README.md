# 🤖 AI Jobs Market 2025-2026 | Análise de Dados

Análise exploratória do mercado global de empregos em Inteligência Artificial, identificando tendências salariais, skills mais demandadas e oportunidades de carreira.

![Status](https://img.shields.io/badge/status-concluído-success)
![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-orange)
![DuckDB](https://img.shields.io/badge/DuckDB-SQL-yellow)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-Dashboard-blueviolet)

---

## 📋 Sobre o Projeto

Este projeto é uma análise completa do mercado de trabalho em IA para 2025-2026, estruturada em 5 fases que demonstram um fluxo profissional de análise de dados: exploração com Python, queries analíticas em SQL, dashboard interativo, apresentação executiva e publicação.

**Objetivo:** Identificar e analisar tendências de salários, skills demandadas e oportunidades no mercado global de IA.

---

## 📊 Dataset

- **Fonte:** [AI Jobs Market 2025-2026 | Salaries (Kaggle)](https://www.kaggle.com/datasets/alitaqishah/ai-jobs-market-2025-2026-salaries)
- **Tamanho:** 1.500 vagas | 25 colunas | 14 países
- **Período:** 2025-2026
- **Proveniência:** Dados compilados de Glassdoor, LinkedIn Workforce Insights, Bureau of Labor Statistics, Ravio Salary Benchmark e outros relatórios públicos de mercado

---

## 🛠️ Stack Utilizada

| Categoria | Ferramentas |
|-----------|-------------|
| **Linguagens** | Python, SQL |
| **Manipulação de dados** | Pandas, NumPy, DuckDB |
| **Visualização** | Matplotlib, Seaborn, Looker Studio |
| **Ambiente** | Jupyter Notebook, VS Code, Google Sheets |
| **Apresentação** | Canva |
| **Versionamento** | Git, GitHub |

---

## 📁 Estrutura do Repositório

```
project_AI_jobs/
├── README.md
├── data/
│   └── ai_jobs_market_2025_2026.csv
├── notebooks/
│   ├── 01_eda.ipynb         # Análise Exploratória
│   └── 02_sql.ipynb         # Queries Analíticas
├── outputs/
│   ├── *.png                # Gráficos exportados
│   └── *.xlsx               # Resultados das queries SQL
├── presentation/
│   └── ai_jobs_market_apresentacao.pdf
└── .gitignore
```

---

## 🚀 Como Rodar

**1. Clone o repositório**
```bash
git clone https://github.com/jovineal/project_AI_jobs.git
cd project_AI_jobs
```

**2. Instale as dependências**
```bash
pip install pandas numpy matplotlib seaborn duckdb openpyxl
```

**3. Abra os notebooks**
```bash
jupyter notebook notebooks/01_eda.ipynb
```

---

## 🔍 Principais Insights

| # | Insight |
|---|---------|
| 1 | **Architecture lidera** com salário médio de **$251k/ano** |
| 2 | **AI Engineering** é o sweet spot — $208k médio com 736 vagas (49% do dataset) |
| 3 | **Python** está presente em **62.8% das vagas** — skill universal |
| 4 | Progressão **Entry → Lead** representa **+60%** de aumento salarial |
| 5 | **ML Operations** lidera o crescimento YoY com **+53%** |
| 6 | **EUA** lidera com salário médio de **$226k** vs. $135k China/Índia |
| 7 | Modalidade de trabalho **não impacta** salário (diferença de ~$5k entre modelos) |
| 8 | **LLM Roles** representam 21.8% das vagas com **prêmio salarial de +8.9%** |

---

## 📈 Dashboard Interativo

Dashboard completo construído no Looker Studio com 4 páginas temáticas:

🔗 **[Acessar Dashboard](https://datastudio.google.com/reporting/eca13b26-aab0-42dc-b5ea-6902201739f3)**

- **Página 1:** Visão Geral (KPIs + distribuição salarial)
- **Página 2:** Salário e Carreira (categoria, experiência, empresa, modalidade)
- **Página 3:** Mercado Global (mapa preenchido + comparativos por país)
- **Página 4:** Skills e Demanda (top skills + crescimento YoY + LLM Roles)

---

## 🎯 Apresentação

Apresentação executiva com os principais insights e respostas para as 8 perguntas de negócio do projeto.

🔗 **[Ver apresentação no Canva](https://canva.link/pb24xdq6fr228p8)**  
📄 **[Baixar PDF](./presentation/ai_jobs_market_apresentacao.pdf)**

---

## 📌 Fases do Projeto

| Fase | Descrição | Entregável |
|------|-----------|-----------|
| 1 | Análise Exploratória com Pandas | `01_eda.ipynb` + 9 gráficos |
| 2 | Análise com SQL (DuckDB) | `02_sql.ipynb` + 6 queries |
| 3 | Dashboard interativo | Looker Studio (4 páginas) |
| 4 | Apresentação executiva | Canva (13 slides) |
| 5 | Publicação | GitHub + LinkedIn |

---

## 👤 Autor

**João Victor Neves Alves**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joao-victor-n-alves-6a26aa288)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/jovineal)

---

> *"A person that uses AI will be so much more productive, they will replace someone that doesn't use AI."*  
> **— Andrew Ng**, World Economic Forum, Davos 2026