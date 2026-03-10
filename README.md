# Análise Financeira de Empresas Brasileiras - Dados CVM

## Descrição do Projeto

Este projeto realiza uma análise financeira das empresas brasileiras utilizando dados das demonstrações financeiras disponibilizadas pela Comissão de Valores Mobiliários (CVM).

O objetivo é extrair, transformar e analisar os dados para gerar indicadores financeiros relevantes e identificar padrões de desempenho entre as empresas.

Foram calculados indicadores como:

- ROE (Return on Equity)
- ROA (Return on Assets)
- Margem Líquida
- Receita de Venda
- Lucro Líquido

A análise busca identificar empresas mais rentáveis, padrões de eficiência operacional e diferenças entre portes de empresa.

---

## Fonte dos Dados

Os dados utilizados neste projeto foram obtidos diretamente da base pública da:

- Comissão de Valores Mobiliários (CVM)

Arquivos de demonstrações financeiras anuais das empresas brasileiras.

---

## Estrutura do Projeto

analise-empresas-cvm
│
├── data
│   ├── dfp_cia_aberta_DRE_2024.csv
│   ├── dfp_cia_aberta_BPA_2024.csv
│   ├── dfp_cia_aberta_BPP_2024.csv
│   └── data_cvm.db
│
├── notebooks
│   ├── EDA.ipynb
│   ├── pipeline_ETL.ipynb
│   ├── analise_financeira_SQL.ipynb
│   └── visualizacoes.ipynb
│
└── README.md

---

## Pipeline de Dados

O projeto segue um pipeline de análise de dados composto por:

1. **Extração de dados** das demonstrações financeiras da CVM  
2. **Transformação e limpeza dos dados** utilizando Python e Pandas  
3. **Armazenamento dos dados em banco SQLite**  
4. **Consultas SQL para cálculo de indicadores financeiros**  
5. **Visualização e análise exploratória dos dados**

---

## Indicadores Financeiros Calculados

Os principais indicadores utilizados na análise foram:

**ROE (Return on Equity)**  
Retorno sobre o patrimônio líquido da empresa.

**ROA (Return on Assets)**  
Eficiência da empresa na utilização de seus ativos.

**Margem Líquida**  
Percentual de lucro obtido sobre a receita total.

---

## Visualizações

O projeto inclui diversas visualizações para análise dos dados:

- Top 10 empresas por ROE
- Relação entre receita de venda e lucro líquido
- Distribuição da margem líquida
- Comparação de ROE entre diferentes portes de empresa

---

## Principais Insights

Algumas observações identificadas durante a análise:

- Empresas de grande porte tendem a apresentar menor volatilidade de ROE.
- Algumas empresas apresentam alta receita, porém baixa rentabilidade.
- A distribuição da margem líquida mostra grande concentração próxima de zero, indicando margens reduzidas em parte das empresas analisadas.

---

## Tecnologias Utilizadas

- Python
- Pandas
- SQL
- SQLite
- Matplotlib / Seaborn
- Google Colab

---

## Autor

Victor Santana
