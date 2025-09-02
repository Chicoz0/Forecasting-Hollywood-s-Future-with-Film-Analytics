# The Next Big Thing: Previsão de Sucesso de Filmes

Este projeto, desenvolvido por Francisco de Paula Lemos, foca em analisar dados de filmes do IMDb para prever o sucesso de bilheteria. A metodologia utilizada é o CRISP-DM (Cross-Industry Standard Process for Data Mining), que guia o processo desde o entendimento do negócio até a modelagem e a entrega de resultados.

O objetivo principal é identificar os fatores que mais influenciam a receita de um filme, fornecendo insights valiosos para a indústria cinematográfica.

## Estrutura do Projeto

O repositório está organizado da seguinte forma:

- `desafio_indicium_imdb.csv`: O conjunto de dados original utilizado para a análise.
- `LH_CD_FRANCISCO_DE_PAULA_LEMOS.ipynb`: O notebook Jupyter que contém toda a análise, desde a Análise Exploratória de Dados (EDA) até a modelagem preditiva.
- `requirements.txt`: Lista de todas as bibliotecas Python necessárias para rodar o projeto.
- `README.md`: Este arquivo, com informações sobre o projeto.
- `imdb_rating_regressor.pkl`: O modelo de machine learning serializado, pronto para ser usado para fazer previsões de receita.
- `best_genre_model.pkl`: Outro modelo de machine learning serializado para prever o gênero de maior sucesso.

## Como Executar o Projeto

Siga os passos abaixo para instalar as dependências e executar a análise:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Chicoz0/Forecasting-Hollywood-s-Future-with-Film-Analytics.git
    cd Forecasting-Hollywood-s-Future-with-Film-Analytics
    ```
2.  **Crie e ative um ambiente virtual (recomendado)::**
    ```bash
    python -m venv venv
    # No Windows
    venv\Scripts\activate
    # No macOS/Linux
    source venv/bin/activate
    ```
3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Execute o notebook:**
    Inicie o Jupyter Notebook ou JupyterLab na raiz do projeto:
    ```bash
    jupyter notebook
    ```
    Ou
    ```bash
    jupyter lab
    ```
    Abra o arquivo `LH_CD_FRANCISCO_DE_PAULA_LEMOS.ipynb` e execute as células para replicar a análise.

## Resultados e Conclusões

A análise e a modelagem detalhadas no notebook revelaram que fatores como o gênero do filme, o número de votos e o histórico de sucesso do diretor e dos atores são fortes indicadores de alta receita. O modelo preditivo desenvolvido é capaz de prever a receita bruta de um filme com base nessas e outras variáveis.

Para mais detalhes sobre as análises estatísticas, a Análise Exploratória de Dados (EDA) e a performance do modelo, consulte o notebook `LH_CD_FRANCISCO_DE_PAULA_LEMOS.ipynb`.
