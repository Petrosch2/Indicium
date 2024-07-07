Instruções para executar e instalar o projeto:

# Análise de Dados Cinematográficos e Predição de Notas IMDB

Este projeto visa realizar uma análise exploratória de dados (EDA) em um conjunto de dados cinematográficos, responder a perguntas específicas relacionadas a filmes, e prever a nota do IMDB de um filme com base em suas características.

## Estrutura do Projeto

- `desafio_indicium_imdb.csv`: Conjunto de dados contendo informações sobre filmes.
- `the_oscar_award.csv`: Conjunto de dados adicionais contendo informações sobre prêmios Oscar. 
- `fonte: https://www.kaggle.com/code/ulrikeherold/the-oscar-award-1927-2024-all-about-movies
- `data_analysis.py`: Script principal que realiza a análise de dados e predição.
- `requirements.txt`: Arquivo de requisitos com todas as dependências do projeto.
- `random_forest_imdb_model.pkl`: Modelo treinado salvo.
- `EDA_Report.pdf`: Relatório da Análise Exploratória de Dados (EDA).

## Pré-requisitos

- Python 3.6 ou superior
- pip (Python package installer)

## Instalação

1. Clone este repositório para o seu ambiente local:

    ```bash
    git clone <URL_do_repositorio>
    cd <nome_do_repositorio>
    ```

2. Crie um ambiente virtual:

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # Para Linux/MacOS
    venv\Scripts\activate     # Para Windows
    ```

3. Instale as dependências:

    ```bash
    pip install -r requirements.txt
    ```

## Execução

1. Certifique-se de que os arquivos `desafio_indicium_imdb.csv` e `the_oscar_award.csv` estão no mesmo diretório que o script `data_analysis.py`.

2. Execute o script principal:

    ```bash
    python data_analysis.py
    ```

3. Após a execução, os seguintes arquivos serão gerados:
    - `random_forest_imdb_model.pkl`: Modelo treinado salvo.
    - `EDA_Report.pdf`: Relatório da Análise Exploratória de Dados (EDA).

## Detalhes do Projeto

### Análise Exploratória de Dados (EDA)

O script `data_analysis.py` realiza uma análise exploratória completa dos dados, incluindo:
- Distribuição das notas do IMDB.
- Frequência dos diferentes gêneros de filmes.
- Distribuição da receita bruta dos filmes.
- Correlação entre variáveis.

### Respostas às Perguntas Específicas

O relatório `EDA_Report.pdf` inclui respostas detalhadas para as seguintes perguntas:
1. **Recomendação de Filme:** Qual filme você recomendaria para uma pessoa que você não conhece?
2. **Fatores de Faturamento:** Quais são os principais fatores que estão relacionados com alta expectativa de faturamento de um filme?
3. **Insights da Coluna Overview:** Quais insights podem ser tirados com a coluna Overview? É possível inferir o gênero do filme a partir dessa coluna?
4. **Previsão de Nota do IMDB:** Como você faria a previsão da nota do IMDB a partir dos dados?

### Modelo de Predição

Um modelo de Random Forest foi treinado para prever a nota do IMDB com base em características do filme. O modelo está salvo como `random_forest_imdb_model.pkl` e pode ser carregado para fazer previsões futuras.

## Contato

Para mais informações, entre em contato com [Petronio Hipolito] em [petronio.hipolito@gmail.com].
