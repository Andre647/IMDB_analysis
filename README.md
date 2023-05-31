# IMDB - Python Notebook
Este projeto consiste em um notebook Python que realiza uma análise de gênero de filmes e atores/atrizes da plataforma do IMDB

## Requisitos
Para o funcionamento do projeto, é necessário possuir instalado 5 datasets, sendo eles:

https://datasets.imdbws.com/

  -> title_basics.tsv
  
  -> name_basics.tsv
  
  -> title_crew.tsv
  
  -> title_ratings.tsv
  
  https://trends.google.com.br/trends/explore?date=all&q=Guerra&hl=pt
  
  -> multiTimeline.csv

## Informações
*Vale ressaltar que o Google Colab não possui memoria o suficiente para armazenar os arquivos TSV title_basics e name_basics por completo, eles tendem a estourar na metade, mas ainda sim o projeto é executável.

*Arquivos TSV(Valores separados por tabulações) é semelhante ao CSV, e por isso, é possivel usar a função read_csv do pandas

*Os dados do IMDB são de certa forma quesionaveis, em multiplos casos é inserido como ator pessoas que foram cameras, escritores etc, isso pode em alguns momentos gerar contradições em algumas analises, mas o dado ser sujo foge do escopo do projeto.

*O maior desafio para realizar o notebook são as colunas de multiplos dados, ao longo do ipynb é possivel ver que varias vezes utilizamos a funcao split para separar em varias colunas dados que estavam em uma só, isso faz com que a coluna de filmes, por exemplo, tenha 3 generos diferentes, o que aumenta a complexidade de analisar um genero especifico.

## Bibliotecas
pandas, numpy, seaborn, matplotlib.pyplot.

## Finalidade
Este projeto está sendo feito como Projeto Semestral para a Materia de Ciencia de Dados do IMT.

Esperamos que este projeto seja útil.Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato.

Aproveite! 🎬
