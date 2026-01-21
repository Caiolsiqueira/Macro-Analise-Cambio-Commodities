# 📊 Análise Macroeconômica: Dinâmica do Câmbio (USD/BRL) e Ciclos de Commodities

> **Status:** Concluído ✅

## 🎯 Objetivo do Projeto
Investigar a relação histórica entre a taxa de câmbio (Real vs Dólar) e os preços internacionais das commodities (Soja e Petróleo) ao longo de 30 anos (1994-2025). O estudo busca validar a hipótese de correlação inversa e identificar anomalias econômicas recentes.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3
* **Fonte de Dados:** Banco Central do Brasil (API SGS) e Yahoo Finance.
* **Bibliotecas:** `pandas`, `seaborn`, `matplotlib`, `python-bcb`, `yfinance`.

## 🔍 Principais Descobertas
1.  **Correlação Inversa:** Historicamente, o "Superciclo das Commodities" (2003-2011) foi o maior responsável pela valorização do Real.
2.  **O Fenômeno do Descolamento (2020-2025):** A partir da pandemia, houve uma quebra estrutural. Mesmo com Soja e Petróleo em máximas históricas, o Dólar permaneceu alto (> R$ 5,00) devido ao aumento do Risco Fiscal.
3.  **Estatística de Probabilidade:** A análise de distribuição (CDF) revelou que em **~79% da história**, o dólar foi negociado abaixo de R$ 4,00, classificando o patamar atual como uma anomalia estatística (cauda longa).

## 📂 Estrutura dos Arquivos
* `BRL_USD_commodities.ipynb`: O código completo em Python com toda a extração, tratamento e geração dos gráficos.
* `BRL_USD_commodities.pdf`: Relatório executivo pronto para impressão/leitura.

---
*Autor: Caio Lucas Siqueira*
*Conecte-se comigo no linkedin.com/in/caio-lucas-siqueira-7py*
