

# Explorando IA Generativa em um Pipeline de ETL com Python

Este projeto tem como objetivo demonstrar como utilizar a Inteligência Artificial Generativa (IA) em um Pipeline de Extração, Transformação e Carga (ETL) para a geração automática de comentários sobre filmes. O pipeline utiliza Python, Pandas, a API do The Movie DB e o modelo GPT-3.5 da OpenAI.

## Contexto

A ideia principal deste projeto é utilizar uma lista de IDs pré-selecionados de filmes armazenados em um arquivo CSV chamado `dioETL.csv`. Para cada ID na lista, o código realiza as seguintes etapas:

1. Consulta a API do The Movie DB para obter informações sobre o filme.
2. Utiliza a API do GPT-3.5 para gerar um comentário sobre o filme com base no título e na descrição.
3. Armazena o comentário gerado na tabela do arquivo CSV, na coluna "comment".
