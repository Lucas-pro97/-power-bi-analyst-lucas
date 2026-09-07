# 📊 Desafio Power BI — Análise Financeira e Territorial (DIO)

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-20629B?style=for-the-badge)

Projeto prático desenvolvido para o bootcamp de **Power BI Analyst** da **[Digital Innovation One (DIO)](https://www.dio.me/)**. 

O objetivo deste projeto é construir um relatório completo e interativo no Power BI com base no *dataset* **Financial Sample**, explorando métricas de vendas, unidades vendidas, produtos e distribuição de lucratividade por segmentos e localização geográfica.

---

## 📌 Visão Geral do Relatório

O relatório é composto por **3 páginas analíticas**, combinando a replicação dos conceitos aprendidos e a criação autônoma de visuais:

### 📄 Página 1: Relatório de Vendas por Produtos
Focus na distribuição de produtos, preços de venda e volume financeiro por ano e segmento.
* **Filtro Temporal (Slicer):** Filtro hierárquico por Ano (`2013`, `2014`) e Trimestres.
* **Soma de Sales por Product (Gráfico de Rosca):** Destaque para os produtos mais vendidos (ex: *Paseo* representando 29,35% das vendas com R$ 27,1 Mi).
* **Contagem de Sale Price por Product (Gráfico de Área):** Acompanhamento do volume de registros de preços por linha de produto.
* **Soma de Sales por Product, Year e Segment (Gráfico de Colunas Agrupadas):** Análise comparativa das vendas entre os segmentos (*Government*, *Small Business*, *Enterprise*, etc.) ao longo dos anos.

---

### 📄 Página 2: Métricas Operacionais e Distribuição Geográfica
Visualização focada em KPIs globais, sazonalidade mensal de lucros e performance por país.
* **Cartões de KPI:**
  * **Soma de Sales:** `24,35 Mi`
  * **Máximo de Units Sold:** `4,24 Mil`
* **Soma de Profit e Primeiro Segment por Month Name (Gráfico de Colunas):** Análise do comportamento do lucro mês a mês.
* **Distribuição por País (Gráfico de Pizza):** Proporção das operações entre os países (*United States*, *Canada*, *France*, *Germany*, *Mexico*).
* **Soma de Sales por Country (Gráfico de Barras/Colunas):** Comparativo direto de faturamento bruto por país.

---

### 📄 Página 3: Análise Territorial e Lucratividade (Desafio Prático)
Página construída autonomamente para avaliação de distribuição geográfica e participação de lucros.

* 🗺️ **Vendas e Unidades Vendidas por País (Visual de Mapa 1):**
  * **Título:** *Vendas e Unidades Vendidas por País*
  * **Métricas:** Localização por `Country`, tamanho pela Soma de `Sales` e detalhamento de `Units Sold` via Dica de Ferramenta (Tooltip).
* 🌎 **Lucro por País (Visual de Mapa 2):**
  * **Título:** *Lucro por País*
  * **Métricas:** Mapeamento do lucro líquido (`Profit`) por país para rápida comparação espacial com o mapa de vendas.
* 🍕 **Lucro por Segmento (Visual de Pizza):**
  * **Título:** *Lucro por Segmento*
  * **Destaques da Análise:**
    * **Government:** Liderança absoluta de lucro com **R$ 11,39 Mi (65,04%)**.
    * **Small Business:** Segundo maior canal com **R$ 4,14 Mi (23,66%)**.
    * **Channel Partners, Midmarket e Enterprise:** Representam os 11,3% restantes.

---

## 🛠️ Boas Práticas e Ajustes Realizados

* **Nomenclatura Direta e Contextual:** Ajuste de títulos para garantir clareza visual (*"Vendas e Unidades Vendidas por País"*, *"Lucro por País"*, *"Lucro por Segmento"*).
* **Dicas de Ferramenta (Tooltips) Otimizadas:** Inclusão de `Units Sold` como dica de ferramenta nos mapas, enriquecendo o contexto sem poluir a interface.
* **Layout Responsivo e Limpo:** Organização em grade equilibrada, facilitando a leitura de topo para base.
* **Acessibilidade:** Aplicação de contraste e legenda explicativa com percentuais e valores absolutos visíveis.

---

## 📁 Arquivos do Repositório

| Arquivo / Pasta | Descrição |
| :--- | :--- |
| 📊 `Financial_Report_DIO.pbix` | Arquivo do projeto para abertura no Power BI Desktop |
| 📑 `Financial_Report_DIO.pptx` | Apresentação exportada / Suplemento do PowerPoint |
| 🖼️ `screenshots/` | Capturas de tela demonstrativas das 3 páginas do relatório |

---

## 🔗 Referências

* **Repositório Base:** Fork do repositório original de [Juliana Zanelatto](https://github.com/julianazanelatto/power_bi_analyst).
* **Dataset:** *Financial Sample* da Microsoft.

---

💡 *Projeto desenvolvido como parte do bootcamp de Power BI Analyst na DIO.*
