# 📊 Relatório de Análise de Desempenho das Lojas

## 🧠 Introdução

> Esse relatório faz parte de um desafio de Data Science proposto pela Alura, onde o objetivo é ajudar o Senhor João a tomar uma decisão importante: qual das suas quatro lojas ele deve vender para fazer um novo empreendimento.Nesse desafio irei apresentar com base nos dados fornecidos qual empresa tem o menor rendimento.  

---
  
## 📈 Análises Realizadas

### 💰 1. Faturamento Total das Lojas

![lucro_por_loja.png](https://github.com/SousaPHP/Challenge-Data-Science-Alura-Store/blob/main/graficos/lucro_por_loja.png?raw=true)

_Análise:_  
Com base nos dados de vendas, percebemos que a **Loja 1** se destaca com o **maior lucro acumulado** entre todas. As **Lojas 2 e 3** também apresentam bons resultados, ficando logo atrás, com valores dentro de uma média considerada positiva.

Já a **Loja 4** chama atenção por estar bem abaixo das demais em termos de faturamento. Embora o gráfico utilize um certo zoom para tornar as diferenças mais visíveis, os números falam por si:

- A diferença de lucro entre a **Loja 4** e a **Loja 3** é de aproximadamente **R\$ 79.527,45**  
- Enquanto entre a **Loja 3** e a **Loja 1**, a diferença é de **R\$ 70.484,09**

Ou seja, a **Loja 4 se destaca negativamente**, ficando para trás quando o assunto é desempenho financeiro.

---

### 🛍️ 2. Categorias de Produtos Mais e Menos Vendidas

![categoria.png](https://github.com/SousaPHP/Challenge-Data-Science-Alura-Store/blob/main/graficos/Vendas%20por%20Categoria%20em%20Cada%20Loja.png?raw=true)

_Análise:_  
Nas vendas por categoria, observamos uma certa homogeneidade na distribuição entre as lojas. Em geral, todos os itens apresentam proporções de vendas bastante semelhantes em cada unidade.

Um destaque importante são os **eletrodomésticos**, cuja quantidade de vendas reflete a posição no ranking de lucros: eles são mais vendidos na **Loja 1** e menos na **Loja 4**, o que reforça a eficiência comercial das lojas.

Já os **brinquedos** e **utilidades domésticas** se destacam como as únicas categorias nas quais a **Loja 4** supera as demais em número de vendas.

---

### ⭐ 3. Média das Avaliações de Clientes por Loja

![media_avaliação](https://github.com/SousaPHP/Challenge-Data-Science-Alura-Store/blob/main/graficos/avaliacoes.png?raw=true)

| Loja   | Média de Avaliação |
|--------|---------------------|
| Loja 1 | ⭐ 3.98 |
| Loja 2 | ⭐ 4.04 |
| Loja 3 | ⭐ 4.05 |
| Loja 4 | ⭐ 4.00 |

_Análise:_  

A média de avaliações é, talvez, o dado mais inconclusivo da análise. Isso porque os valores entre as lojas são muito próximos, a diferença entre a maior e a menor nota é de apenas **0.07 pontos**. A proximidade indica que a experiência do cliente, no geral, é parecida entre as lojas, e não é um fator determinante para indicar a eficiência de cada uma, já que a loja com menor nota tambem é a com maior lucro.

---

### 🥇 4. Produtos Mais e Menos Vendidos

![produtos_mais_vendidos](https://github.com/SousaPHP/Challenge-Data-Science-Alura-Store/blob/main/graficos/Produtos%20Mais%20Vendidos%20por%20Loja.png?raw=true)

![produtos_menos_vendidos](https://github.com/SousaPHP/Challenge-Data-Science-Alura-Store/blob/main/graficos/Produtos%20Menos%20Vendidos%20por%20Loja.png?raw=true)


_Análise:_  
Nestes gráficos conseguimos identificar um possível fator para o baixo lucro da **Loja 4**. Alguns dos produtos mais vendidos na **Loja 1**, como a **TV LED UHD 4K**, estão entre os **menos vendidos** da **Loja 4**. O mesmo acontece com outros itens de alto valor, como guarda-roupas.

Isso sugere que a **Loja 4 vende menos itens de maior valor**, o que impacta  no seu faturamento. As demais lojas apresentam uma **maior diversidade** nas vendas, o que ajuda a manter um desempenho mais equilibrado.

---

### 🚚 5. Frete Médio por Loja

![media_frete](https://github.com/SousaPHP/Challenge-Data-Science-Alura-Store/blob/main/graficos/media_frete.png?raw=tree)

_Análise:_  
Aqui vemos um dado interessante, diferente do que poderíamos pensar: o menor frete, que seria o mais atrativo a compras, fica com a loja 4 e o valor vai aumentando até a loja 1, que fica com o maior frete. Algo que pode se deduzir aqui é que, como o valor dos itens mais comprados é menor, o valor do frente também é, e como a loja 1 vende mais produtos com alto valor, o frente acompanha esse preço.

---

## 🗺️ Extra! Análise de Desempenho Geográfico

![Mapa de Calor](https://github.com/SousaPHP/Challenge-Data-Science-Alura-Store/blob/main/graficos/HeatMap.png?raw=true)

Aqui exploramos as coordenadas de **latitude e longitude** para entender a distribuição geográfica das vendas de cada loja.

Os mapas de calor mostram uma maior concentração de vendas em **regiões específicas**, que se repetem entre as 4 lojas. É possível perceber uma **baixa presença de vendas na região Norte**, enquanto **Sudeste, Centro-Oeste e Nordeste** se destacam como as áreas com maior volume de vendas.

---

## 📈 Extra! Avaliação de Vendas por Ano

![Vendas por ano 2020-2022](https://github.com/SousaPHP/Challenge-Data-Science-Alura-Store/blob/main/graficos/Vendas%20ano.png?raw=true)
![Vendas por ano 04/2020-03/2022](https://github.com/SousaPHP/Challenge-Data-Science-Alura-Store/blob/main/graficos/Vendas%20no%20ultimo%20ano.png?raw=true)

Para complementar a análise, eu decidi por fazer mais um grafico comparando as vendas de cada loja ao decorrer dos 3 anos e 3 meses que estão presentes nos dados:

1. Vendas por loja entre os anos de **2020 a 2022**  
  As **Lojas 1, 2 e 3** começam com um número de vendas menor do que a **Loja 4**, mas ao longo do tempo demonstram um crescimento constante. Já a **Loja 4 apresenta queda nas vendas durante todo o período**.

2. Vendas de **abril de 2022 a março de 2023**  
  Para observar o último ano completo de dados, analisamos as vendas de abril de 2022 a março de 2023. Aqui, notamos que a **Loja 4 apresenta uma grande oscilação nas vendas** e termina o período com **um desempenho abaixo** das outras unidades.

---

## ✅ Conclusão

Após a análise detalhada de todos os fatores, a loja recomendada para ser **vendida** é a:

### 🏁 **Loja 4**

**Justificativa da escolha:**

A Loja 4 **apresentou o menor desempenho** em vários indicadores, como **faturamento total, vendas por categoria e produtos mais vendidos**. Além disso, a loja que segundo os dados já registrava **vendas de menor valor** tambem demonstra estar em **queda no numero de vendas**. Dessa forma, essa unidade é a que mais se distancia dos padrões de eficiência observados nas demais lojas da rede.

---

