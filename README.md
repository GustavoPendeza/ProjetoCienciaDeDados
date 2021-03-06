# Projeto Ciência de Dados Airbnb Rio

Esse projeto foi desenvolvido no curso Python Impressionador da Hashtag Treinamentos.

## Objetivo

Construir um modelo de previsão de preço que permita uma pessoa comum que possui um imóvel possa saber quanto deve cobrar pela diária do seu imóvel.

Ou ainda, para o locador comum, dado o imóvel que ele está buscando, ajudar a saber se aquele imóvel está com preço atrativo (abaixo da média para imóveis com as mesmas características) ou não.

## Modelos de previsão

Foram utilizados para teste os modelos:
- Random Forest
- Linear Regression
- Extra Trees

O modelo com os melhores resultados e que foi escolhido ao final foi o Extra Trees.

## Como testar

Baixe e extraia os arquivos na pasta do projeto: https://drive.google.com/drive/folders/1aqFpNvZ1hukEEeudLXsKAazWGwGWo5VV?usp=sharing

Os arquivos do link incluem: bases dos dados utilizados no projeto e "modelo.joblib"(que é o arquivo com tudo já feito e testado sobre os modelos de previsão. Ele é utilizado pelo "DeployProjetoAribnb.py" para fazer a previsão de preço). Esses arquivos estão no Drive pois são grandes demais e o GitHub não aceita arquivos acima de 50mb.

Instale todas as dependências do "DeployProjetoAirbnb.py" e rode ele pelo prompt(de preferência o prompt do Anaconda3) usando o comando:
- streamlit run DeployProjetoAirbnb.py

<p>Para fazer testes você pode usar os dados que estão no documento "Dados para teste.txt" para ter uma base de como funciona e depois ir alterando os valores.</p>

Tenha em mente que por ser uma análise de dados, pode ser que demore alguns minutos para que ele faça a previsão do preço. Ele inclusive, depende do seu computador para rodar a previsão, então quanto pior o computador mais tempo levará.
