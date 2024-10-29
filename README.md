# Análise de Avaliações de Filmes

Este projeto realiza a análise de resenhas de filmes em português e inglês, utilizando a biblioteca PySpark para processamento de dados em grande escala.

## Descrição

O código apresentado neste repositório carrega um conjunto de dados de resenhas de filmes, filtra as resenhas negativas e realiza a contagem de palavras em português e inglês. O resultado inclui a soma total de palavras em cada idioma e a diferença entre as contagens.

## Estrutura do Projeto

O projeto contém os seguintes arquivos principais:

- `imdb-reviews-pt-br.csv`: arquivo CSV com as resenhas de filmes.
- `analyze_sentiment.py`: script principal que contém o código para análise.

## Dependências

Certifique-se de ter as seguintes dependências instaladas:

- [Python](https://www.python.org/)
- [PySpark](https://spark.apache.org/docs/latest/api/python/index.html)

Você pode instalar o PySpark usando o pip:

```bash
pip install pyspark

