<h1 align="center">
    <p style="font-size: 30px;">
    Projeto de Análise de Dados com o Brazilian E-Commerce Public Dataset 
    </p>
</h1>

## 📌 Descrição dos dados
Este repositório contém as análises e insights extraídos a partir do **Brazilian E-Commerce Public Dataset** <a href="https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce" target="_blank">(Acesse no Kaggle)</a>.  O dataset abrange dados de múltiplos marketplaces no Brasil e oferece a oportunidade de explorar diversas áreas, como comportamento de clientes, desempenho de vendedores, preços de produtos e análises temporais.


### ▶ Esquema de datasets
<img src="./img/schema_.png" />

No esquema acima é possível observar que os datasets são interligados por chaves estrangeiras, o que permite realizar `merges` e obter análises mais complexas e interessantes ao combinar diferentes informações. <br>
<label style="font-weight: bold;">OBS:</label> O conjunto de dados geográfico marcado com o `X` não foi utilizado na em nenhuma análise.



## 🛠️ Ferramentas e Bibliotecas

* **Linguagem:** Python 3.11
* **Ambiente de Desenvolvimento:** Jupyter Lab
* **Gerenciamento de Ambiente:** Miniconda 3
* **Bibliotecas:** Pandas, NumPy, SciPy, Matplotlib e Seaborn

## 🔎 Análises

### Top 10 categorias com maior receita
<img src="./plots/top10_categories_highest_revenue.png">

### Top 10 categorias com menor receita
<img src="./plots/top10_categories_lowest_revenue.png">

### Top 10 vendedores com maior receita
<img src="./plots/top_10_highest_sellers.png">


### Top 6 produtos com maior quantidade de vendedores
<img src="./plots/product_with_most_sellers_1.png">

### Vendedores com maiores reviews baseado na quantidade de vendas
<img src="./plots/sellers_with_best_reviews.png">

### Correlação entre o número de vendas e o número de reviews por seller
<img src="./plots/num_sells_num_reviews.png">

### A presença de uma review escrita influencia na nota?

#### Com mensagem de review
<img src="./plots/comments_by_sentiment_with_review_message.png">


#### Sem mensagem de review
<img src="./plots/comments_by_sentiment_with_review_no_message.png">


### Cidades com maior receita
<img src="./plots/top10_highest_sales_cities.png">

### Estados com maior receita
<img src="./plots/top12_states_highest_sales.png">


### Os produtos tiveram inflação ao longo do tempo?

#### Produto P_656e0eca
<img src="./plots/product_inflation_P_656e0eca.png">

#### Produto P_d285360f
<img src="./plots/product_inflation_P_d285360f.png">

#### Produto P_e0d64dcf
<img src="./plots/product_inflation_P_e0d64dcf.png">