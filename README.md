# 🛒 Análise de indicadores das lojas do Sr. João - Challenge

![Versão](https://img.shields.io/badge/vers%C3%A3o-1.0-blue)
![Status](https://img.shields.io/badge/status-Em%20desenvolvimento-yellow)

## 📊 Sobre o Projeto

Este projeto realiza uma análise exploratória dos dados de quatro lojas do Sr. João, com o objetivo de fornecer informações estratégicas que o ajudem a decidir qual loja vender. A análise é feita utilizando Python (pandas, matplotlib) e está estruturada em um notebook Jupyter.

| Indicadores Utilizados           | Objetivo                                  |
| -------------------------------- | ----------------------------------------- |
| ✅ Faturamento total por loja     | Identificar qual loja gera mais receita   |
| ✅ Vendas por categoria           | Compreender o foco de vendas de cada loja |
| ✅ Produtos mais e menos vendidos | Avaliar desempenho por produto            |
| ✅ Média das avaliações           | Analisar a satisfação dos clientes        |
| ✅ Valor médio de frete           | Estimar impacto logístico por loja        |


---

## 💰 Faturamento total por loja

Nesta seção, avaliamos o total arrecadado por cada loja, considerando o volume de vendas e os valores envolvidos. O objetivo é entender qual loja gera mais receita de forma geral.

![Faturamento das Lojas](https://raw.githubusercontent.com/FalkonGangrel/challenge1-data-science/main/img/Faturamento.png)

**Análise:**

- **Loja 1** apresenta o maior faturamento, indicando um desempenho superior em vendas.  
- **Loja 4** possui o menor faturamento, sugerindo uma performance abaixo das demais.

---

## 📦 Vendas de produtos por categoria

A análise por categoria permite identificar quais tipos de produtos são mais vendidos em cada loja, ajudando a compreender o foco e a especialização de cada uma.

![Vendas por Categoria](https://raw.githubusercontent.com/FalkonGangrel/challenge1-data-science/main/img/Categoria.png)

**Análise:**

- **Loja 2** destaca-se na venda de eletrônicos, indicando uma especialização nesse segmento.  
- **Loja 3** possui uma distribuição mais equilibrada entre as categorias, sugerindo uma abordagem mais diversificada.

---

## 🛍️ Venda de produtos

Análise dos 5 produtos com maior e menor número de vendas e faturamento em cada loja, exibida em uma matriz de gráficos (4x4) para facilitar a comparação.
Aqui investigamos as quantidades totais de produtos vendidos por loja. Essa métrica ajuda a entender o volume de vendas independentemente do valor.

![Produtos Mais Vendidos e Mais Faturados](https://raw.githubusercontent.com/FalkonGangrel/challenge1-data-science/main/img/Produtos.png)

**Análise:**

- **Loja 1** possui os produtos mais vendidos e com maior faturamento, reforçando seu destaque no mercado.  
- **Loja 4** apresenta produtos com menor volume de vendas e faturamento, indicando uma possível necessidade de revisão de estratégias.


---

## 🌟 Média das avaliações

As avaliações dos clientes foram analisadas para verificar o nível de satisfação em cada loja, o que é um indicador importante para avaliar a qualidade do atendimento e dos produtos.

![Média das Avaliações](https://raw.githubusercontent.com/FalkonGangrel/challenge1-data-science/main/img/Avaliacao.png)

**Análise:**

- **Loja 3** possui a maior média de avaliações, sugerindo um alto nível de satisfação dos clientes.  
- **Loja 2** apresenta a menor média, indicando possíveis áreas de melhoria no atendimento ou na qualidade dos produtos.

---

## 🚚 Valor de frete por loja

Essa análise mostra o custo médio de frete por loja, permitindo verificar se o custo logístico pode impactar a margem de lucro ou a experiência do cliente.

![Valor Médio de Frete](https://raw.githubusercontent.com/FalkonGangrel/challenge1-data-science/main/img/Frete.png)

**Análise:**

- **Loja 4** apresenta o maior valor médio de frete, o que pode afetar negativamente a experiência do cliente e as vendas.  
- **Loja 1** possui o menor custo de frete, potencialmente contribuindo para sua liderança em faturamento.

---

## ✅ Conclusão

Com base nos indicadores analisados — faturamento, volume de vendas, categorias, avaliações e frete — o Sr. João poderá tomar uma decisão mais embasada sobre qual loja vender. A combinação entre performance financeira e satisfação do cliente permite uma visão estratégica completa.
Sugestão: Com base nas anãlises acima, a venda da loja 4 é mais indicada pela baixa performance em relação às outras lojas.

---
