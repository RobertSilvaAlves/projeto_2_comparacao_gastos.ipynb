# 📊 Projeto 2 — Análise Comparativa de Gastos Mensais
## 📌 Contexto

Este projeto tem como objetivo comparar os gastos financeiros entre dois meses consecutivos (Janeiro e Fevereiro), identificando variações por categoria e no total, a fim de compreender mudanças no comportamento financeiro.

O projeto foi desenvolvido utilizando Python e Matplotlib, com foco em lógica, organização de dados e visualização — sem uso de bibliotecas avançadas como Pandas, respeitando o nível atual de aprendizado.

---

## 🧩 Estrutura dos Dados

Os dados estão organizados em um dicionário no seguinte formato:

- Mês

- - Categoria de gasto

- - Valor gasto

Exemplo:

```
{
  'JANEIRO': {
      'Alimentação': 800,
      'Transporte': 520,
      'Lazer': 240,
      'Moradia': 1200,
      'Financiamento': 1500
  },
  'FEVEREIRO': {
      'Alimentação': 780,
      'Transporte': 430,
      'Lazer': 280,
      'Moradia': 1200,
      'Financiamento': 1500
  }
}
```

Essa estrutura facilita:

- Acesso direto por mês e categoria

- Comparações entre períodos

- Evolução futura para análise temporal

---

## 🛠️ Funcionalidades Desenvolvidas

- **✔️ Cálculo do total de gastos por mês**

- - Soma automática dos valores de cada categoria.

- **✔️ Comparação entre meses**

- - Identificação do mês com maior gasto total.

- - Cálculo da diferença entre os meses.

- - Indicação de aumento ou redução nos gastos.

- **✔️ Análise de variação por categoria**

- - Cálculo da diferença de gastos entre os meses.

- - Identificação de categorias com aumento, redução ou estabilidade.

- - Destaque da categoria com maior variação absoluta.

---

## 📈 Visualizações

- 🔹 Gráfico 1 — Gastos Totais por Mês

> Comparação direta do total gasto em Janeiro e Fevereiro.

- 🔹 Gráfico 2 — Gastos por Categoria

> Visualização lado a lado dos gastos por categoria em cada mês.

- 🔹 Gráfico 3 — Variação por Categoria

> Gráfico de barras com valores positivos e negativos, facilitando a identificação de aumentos e reduções nos gastos.

---

## Principais Aprendizados

- Organização de dados em dicionários

- Criação e reutilização de funções

- Uso de laços (for) para evitar repetição de código

- Interpretação de valores positivos e negativos

- Comunicação de insights por meio de visualizações

## Próximos Passos

- Expandir a análise para mais meses

- Trabalhar com dados temporais

- Introduzir bibliotecas como Pandas futuramente

## 👤 Autor
**Robert Alves** 

## -  Projeto desenvolvido para fins educacionais e construção de portfólio em Data Analytics (nível júnior).