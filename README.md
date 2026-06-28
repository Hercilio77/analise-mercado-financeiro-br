# Análise do Mercado Financeiro Brasileiro

## Problema

Como os principais indicadores macroeconômicos brasileiros se comportaram nos últimos 5 anos e qual o impacto da SELIC na inflação e no câmbio.

## Perguntas de Negócio

- Como a SELIC evoluiu nos últimos 5 anos e quais foram os momentos de inflexão?

- Existe correlação entre a taxa SELIC e o IPCA (inflação)?

- Como o câmbio USD/BRL reagiu às mudanças na taxa de juros?

- Qual período foi o mais crítico para a economia brasileira no intervalo analisado?

## Fonte dos Dados

- [API SGS - Banco Central do Brasil](https://api.bcb.gov.br)
- Séries: SELIC (432), IPCA (433), Câmbio USD/BRL (1)
- Período: Janeiro/2020 até hoje

## Tecnologias

Python, Pandas, Requests, Jupyter Notebook

## Solução

Coleta Automatizada via API do Banco Central, tratamento dos dados com Pandas e análise exploratória com visualizações em Python para identificar padrões e correlações entre os indicadores.

## O que foi feito

- Coleta e tratamento de dados das séries históricas do Banco Central
- Análise da evolução da SELIC com identificação dos momentos de inflexão
- Cálculo e visualização da correlação entre SELIC, IPCA e Câmbio (USD/BRL)
- Geração de gráficos de linhas, dispersão e heatmaps para comunicar os padrões encontrados

## Principais Insights

- A correlação entre SELIC e IPCA foi de -0.16, indicando relação negativa fraca, o efeito da política monetária na inflação ocorre com defasagem de 6 a 12 meses
- A correlação entre SELIC e Câmbio foi de 0.002, praticamente nula no período
- A correlação entre Câmbio e IPCA foi de 0.03, outros fatores como pandemia e energia dominaram o IPCA no período analisado