# Netflix Data Analysis

Este projeto apresenta uma análise de dados referente ao conjunto de dados da Netflix disponível no [Kaggle](https://www.kaggle.com/datasets/ankulsharma150/netflix-data-analysis). A análise foi realizada com o objetivo de responder a perguntas específicas sobre filmes e programas de TV disponíveis na plataforma. As perguntas abordadas incluem a quantidade de lançamentos por mês, contagem de classificações (ratings), filmes de atores populares de Bollywood, e uma análise sobre diretores.

## 1. Lançamentos de Filmes e Programas de TV por Mês

A análise revelou o padrão de lançamentos de filmes e programas de TV ao longo do tempo. Para isso, foi extraída a coluna `date_added` e transformada para focar no mês de lançamento.

![Lançamentos por Mês]([Movies and Series Releases by Month.png](https://github.com/MarcoABsouza/Netflix-Data-Analysis/blob/main/Movies%20and%20Series%20Releases%20by%20Month.png))

A maioria dos lançamentos ocorre no final do ano, com picos notáveis em dezembro, provavelmente devido ao aumento de produções durante as festividades. Isso pode indicar uma estratégia da Netflix para maximizar a audiência durante o período de férias.

## 2. Contagem de Classificações (Ratings) Únicas e a Classificação com o Maior Número

A análise dos tipos de classificação (rating) mostrou quantos tipos únicos existem e qual classificação aparece com mais frequência no catálogo da Netflix.

![Distribuição de Ratings]([link-para-o-gráfico](https://github.com/MarcoABsouza/Netflix-Data-Analysis/blob/main/Unique%20Rating%20Values%20and%20Their%20Frequency.png))

Aqui estão os principais insights:
- A classificação `TV-MA` (mature audience) aparece com maior frequência no catálogo, seguida por `TV-14`. Isso indica uma predominância de conteúdo para público adulto e adolescente.
- O catálogo também possui uma quantidade significativa de conteúdo infantil com a classificação `TV-Y` e `TV-Y7`.

## 3. Filmes de Salman Khan, Shah Rukh Khan e Akshay Kumar

Um ponto de interesse foi verificar quais filmes dos atores populares Salman Khan, Shah Rukh Khan e Akshay Kumar estão disponíveis na plataforma. Isso foi feito com base na coluna `cast` que lista os atores dos filmes e programas.

![Filmes dos Atores de Bollywood](link-para-o-gráfico)

Aqui estão as quantidades de filmes desses atores na Netflix:
- **Salman Khan:** 5 filmes
- **Shah Rukh Khan:** 8 filmes
- **Akshay Kumar:** 7 filmes

Isso reflete o impacto global que esses atores têm, com suas obras disponíveis para um público internacional.

## 4. Adições Anuais de Programas e Filmes por Tipo

Para observar o crescimento do catálogo ao longo dos anos, foi analisado o número de adições de novos títulos por tipo (filme ou programa de TV) em uma base anual.

![Adições por Ano](link-para-o-gráfico)

A análise revelou:
- Um aumento constante de novos conteúdos até 2020, quando houve um pico significativo. Isso pode estar relacionado ao aumento na demanda por streaming durante a pandemia de COVID-19.
- Após 2020, houve uma leve queda no número de adições, possivelmente refletindo as interrupções de produção e ajustes na estratégia de conteúdo da Netflix.

## 5. Diretores com Mais Programas de TV

A última análise focou nos diretores que produziram o maior número de programas de TV na plataforma. Utilizando a coluna `director`, filtramos os diretores que são mais ativos em produções de TV.

![Diretores Populares](link-para-o-gráfico)

O diretor com o maior número de programas de TV dirigidos é **Alastair Fothergill**, conhecido por seu trabalho em documentários sobre a natureza.

## Conclusão

Este relatório oferece uma visão inicial sobre o catálogo da Netflix, abordando tanto tendências de lançamento quanto a presença de atores e diretores populares. Além disso, as análises revelam as classificações mais comuns e o crescimento do catálogo ao longo do tempo. Isso pode servir como base para estudos mais aprofundados sobre a estratégia de conteúdo da Netflix.

---

### Ferramentas Utilizadas:
- **Python:** Pandas, Matplotlib, Seaborn
- **Dataset:** [Netflix Dataset from Kaggle](https://www.kaggle.com/datasets/ankulsharma150/netflix-data-analysis)

