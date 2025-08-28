# 🍕 Regressão Linear com Vendas de Pizza

Este projeto tem como objetivo analisar e prever as vendas de pizza em um supermercado de Belém durante o ano de 2023 usando regressão linear e o processo KDD (Knowledge Discovery in Databases) para identificar padrões e realizar previsões baseadas nos dados históricos. O projeto inclui tanto a implementação manual da regressão linear quanto o uso da biblioteca scikit-learn.

## Objetivos

- Explorar os dados de vendas de pizza do supermercado.
- Aplicar o processo KDD para extração de conhecimento.
- Construir modelos de regressão linear manualmente e com scikit-learn.
- Avaliar a performance dos modelos na previsão de vendas.

## Tecnologias

- Python 3.12
- **pandas** – manipulação de dados
- **matplotlib** e **seaborn** – visualização de dados
- **scikit-learn** – modelo de regressão linear
- **Jupyter Notebook** – ambiente de desenvolvimento
- **uv** – gerenciador de pacotes

## Execução

1. Clone este repositório:
    ```
    git clone https://github.com/marcosnevary/pizza-sales-linear-regression.git
    cd pizza-sales-linear-regression
    ```
2. Instale as dependências:
    ```
    uv sync
    ```
3. Abra o notebook:
    ```
    uv run --with jupyter jupyter lab
    ```