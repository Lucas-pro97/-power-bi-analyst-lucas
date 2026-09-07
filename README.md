# 📊 Dashboard Financeiro — Power BI Analyst

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis-blue)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-BI-green)
![Status](https://img.shields.io/badge/Status-Concluído-success)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte do **Bootcamp Power BI Analyst da DIO**, com o objetivo de colocar em prática conceitos de **Business Intelligence, análise de dados e visualização de informações utilizando Microsoft Power BI**.

O desafio consiste na reprodução de páginas apresentadas durante o curso e na criação de uma terceira página autoral, explorando diferentes tipos de visuais e recursos de interação.

Além de atender aos requisitos propostos no desafio, o projeto foi estruturado pensando também em boas práticas de apresentação e organização de um relatório de Business Intelligence.

---

## 🎯 Objetivo

Construir um relatório capaz de apresentar informações financeiras e comerciais de forma visual e intuitiva, permitindo analisar:

- 💰 Vendas (Sales)
- 📈 Lucro (Profit)
- 📦 Unidades vendidas (Units Sold)
- 🌎 Distribuição geográfica dos resultados
- 🏢 Desempenho por segmento
- 📊 Desempenho de vendas por produto

O projeto busca transformar dados brutos em informações que possam apoiar uma análise mais rápida do desempenho comercial e financeiro.

---

## 🛠️ Tecnologias e Ferramentas

- **Microsoft Power BI**
- **DAX**
- **Power BI Service**
- **Microsoft PowerPoint**
- **Git**
- **GitHub**
- **Data Visualization**
- **Business Intelligence**

---

# 📊 Estrutura do Dashboard

O relatório é composto por três páginas principais.

---

## 1️⃣ Página 1 — Relatório de Vendas por Produtos

Nesta página são apresentados visuais relacionados ao desempenho de vendas dos produtos.

### Principais análises:

- Vendas por produto
- Vendas por produto e segmento
- Evolução das vendas
- Distribuição das vendas entre produtos
- Quantidade de vendas por produto
- Análise utilizando hierarquia de Ano, Trimestre, Mês e Dia

### Visuais utilizados:

- Gráfico de pizza
- Gráfico de área
- Gráfico de colunas
- Hierarquia temporal

---

## 2️⃣ Página 2 — Análise Financeira

A segunda página apresenta uma visão geral dos principais indicadores financeiros e comerciais.

### Principais indicadores:

- Total de Sales
- Units Sold
- Distribuição por país
- Evolução do Profit
- Vendas por país

Essa página permite uma visão mais ampla do desempenho financeiro e da distribuição dos resultados entre os diferentes mercados.

---

## 3️⃣ Página 3 — Análise Geográfica e Lucratividade

A terceira página foi desenvolvida para atender ao desafio proposto no módulo de mapas do Bootcamp.

### 🌎 Visual 1 — Vendas e Unidades Vendidas por País

Apresenta a distribuição geográfica das vendas e das unidades vendidas.

**Principais campos utilizados:**

- Country
- Sales
- Units Sold

---

### 💰 Visual 2 — Lucro por País

Apresenta a distribuição geográfica do lucro entre os países analisados.

**Principais campos utilizados:**

- Country
- Profit

Informações complementares podem ser disponibilizadas por meio de **Tooltips**, permitindo consultar outras métricas sem comprometer a visualização principal.

---

### 🍕 Visual 3 — Lucro por Segmento

O gráfico de pizza apresenta a participação de cada segmento no lucro total.

Os segmentos analisados são:

- Government
- Small Business
- Channel Partners
- Midmarket
- Enterprise

---

# 🔎 Principais Insights

A análise dos dados permite identificar alguns pontos relevantes.

### 💡 01 — Concentração de lucro

O segmento **Government** apresenta a maior participação no lucro total, representando aproximadamente **65%** do resultado apresentado no gráfico de lucro por segmento.

Esse resultado demonstra uma concentração significativa da lucratividade nesse segmento.

---

### 💡 02 — Desempenho geográfico

Os mapas permitem comparar visualmente o desempenho dos diferentes países em relação a:

- Sales
- Profit
- Units Sold

Essa visualização facilita a identificação dos mercados que apresentam maior contribuição para os resultados.

---

### 💡 03 — Volume x resultado

A comparação entre **Sales, Units Sold e Profit** permite analisar não apenas o volume de vendas, mas também o impacto dessas vendas na geração de lucro.

Essa abordagem ajuda a diferenciar mercados com alto volume de vendas daqueles que apresentam maior contribuição financeira.

---

# 🎨 Visualização e Organização

Durante a construção do relatório foram considerados alguns princípios de visualização de dados:

- Organização dos visuais por contexto
- Títulos claros e objetivos
- Distribuição equilibrada dos gráficos
- Utilização de mapas para análise geográfica
- Utilização de gráfico de pizza para participação por segmento
- Uso de Tooltips para informações complementares
- Hierarquia visual para facilitar a interpretação dos dados

O objetivo foi manter o relatório simples, organizado e de fácil compreensão.

---

# 📐 Conceitos Praticados

Este projeto permitiu praticar conceitos importantes de Power BI, incluindo:

- Importação e utilização de datasets
- Criação de relatórios
- Criação e configuração de visuais
- Mapas no Power BI
- Gráficos de pizza
- Gráficos de colunas
- Gráficos de área
- Hierarquia de datas
- Segmentação e análise de dados
- Tooltips
- Formatação de relatórios
- Publicação no Power BI Service
- Integração com PowerPoint
- Versionamento utilizando Git e GitHub

---

# 📁 Estrutura do Repositório

```text
-power-bi-analyst-lucas/
│
├── 📁 dashboard/
│   └── Financial_Report_DIO.pbix
│
├── 📁 presentation/
│   └── Analista-Power-BI-Desafio.pptx
│
├── 📁 screenshots/
│   ├── pagina-1.png
│   ├── pagina-2.png
│   └── pagina-3.png
│
├── 📁 dataset/
│   └── Financial Sample.xlsx
│
└── README.md
