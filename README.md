# Challenge Alura Store
## Alura + Oracle | Oracle Next Education | Tech Foundation
### Especialização Data Science

Respositório com a solução do desafio _Alura Store_ do **Programa ONE**.

## 🎯 Sobre o Desafio 🎯
Ajudar o Senhor João a decidir qual loja da sua rede Alura Store vender para iniciar um novo empreendimento. Para isso, será analisado dados de vendas, desempenho e avaliações das 4 lojas fictícias da Alura Store. O objetivo é identificar a loja com menor eficiência e apresentar uma recomendação final baseada nos dados.

## 🛠 Recursos Utilizados 🛠
Ferramentas, linguagens, bibliotecas e outros recursos usados na resolução do desafio:

![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Folium](https://img.shields.io/badge/Folium-77B829?style=for-the-badge&logo=folium&logoColor=white)

# 🔎 Análises 🔍
As análises realizadas teve como objetivo avaliar informações como **faturamento, categorias mais vendidas, avaliações dos clientes, produtos mais e menos vendidos e frete médio**.

## 💰 Faturamento Total de Cada Loja 💰
Calcular o **faturamento total de cada loja**, somando os valores da coluna **Preço** de cada loja para estimar o faturamento.

<img src="/imagens/faturamento.png">

O gráfico ilustra o faturamento total de cada loja. A Loja 1 lidera com o maior faturamento, totalizando R$ 1.534.509,12, seguida pela Loja 2 com R$ 1.488.459,06, Loja 3 com R$ 1.464.025,03 e, por último, a Loja 4 com R$ 1.384.497,58. Assim, podemos concluir que a Loja 1 obteve o melhor desempenho em faturamento, enquanto a Loja 4 apresentou o menor.

## 🛒 Vendas por Categoria 🛒
Calcular a **quantidade de produtos vendidos por categoria** em cada loja. A ideia é agrupar os dados por categoria e contar o número de vendas de cada tipo, mostrando as **categoria mais populares** de cada loja.

<img src="/imagens/vendascategorias.png">

O gráfico ilustra a participação de cada categoria de produtos no faturamento de cada loja. O objetivo foi identificar as categorias que mais contribuem para o faturamento e aquelas com menor impacto. Observou-se que a categoria de móveis é a principal responsável pelo faturamento em todas as lojas. Por outro lado, a contribuição das categorias de utilidades domésticas, instrumentos musicais e livros apresentou flutuações, indicando variações em seu desempenho.

## 🌟 Média de Avaliação por Loja 🌟
Calcular a média das avaliações dos clientes para cada loja, com o objetivo de **entender a satisfação dos clientes com os produtos vendidos**.

<img src="/imagens/avaliacao.png">

O gráfico ilustra a avaliação média da satisfação dos clientes em relação a cada loja, mensurada em uma escala de 1 a 5. A Loja 3 lidera em satisfação, com uma média de avaliação de 4,05, seguida pela Loja 2 com 4,04, Loja 4 com 4,00 e, por último, a Loja 1, com 3,98. Assim, podemos concluir que a Loja 3 obteve a melhor avaliação entre os clientes, enquanto a Loja 1 apresentou a pior, embora a diferença seja de apenas 0,07.
O gráfico apresenta uma linha que representa a média da avaliação geral entre as lojas, permitindo observar quais estão acima ou abaixo da média de satisfação de todas as lojas.

## 📈 Produtos Mais e Menos Vendidos 📉
Identificar quais produtos foram os mais vendidos e os menos vendidos em cada loja.  Ao final, visualizar os resultados de forma que fique claro quais produtos se destacaram nas vendas de cada loja.

<img src="/imagens/maismenosvendido.png">

O gráfico ilustra os produtos mais e menos vendidos de cada loja. Podemos observar que a variação entre o produto mais vendido e o menos vendido em cada loja é significativa. Na Loja 1, o guarda-roupas teve 60 unidades vendidas, enquanto o celular ABXY vendeu 33 unidades. Na Loja 2, o livro "Iniciando em Programação" alcançou 65 unidades vendidas, enquanto o jogo de tabuleiro vendeu apenas 32. Na Loja 3, o kit de banquetas teve 57 unidades vendidas, enquanto o bloco de montar vendeu somente 35. Por fim, na Loja 4, a cama box vendeu 62 unidades, enquanto a guitarra teve 33 unidades vendidas.

## 🚛 Frete Médio por Loja 🚛
Calcular o custo médio de frete para cada loja. O objetivo é entender quanto, em média, está sendo gasto com frete para cada uma das lojas.

<img src="/imagens/fretemedio.png">

O gráfico ilustra o custo médio com frete em cada loja. Considerando a ordem a partir do maior custo médio, a Loja 1 apresenta um custo de R$ 34,69, seguida pela Loja 2 com R$ 33,62, Loja 3 com R$ 33,07 e, por último, a Loja 4, com o menor custo médio, de R$ 31,28. O gráfico também apresenta uma linha que representa o custo médio do frete considerando todas as lojas, permitindo observar quais estão acima ou abaixo da média geral do custo de frete.

## 📋 Relatório Final 📋
