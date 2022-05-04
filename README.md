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

Instale todas as dependências do "DeployProjetoAirbnb.py" e rode ele pelo prompt(de preferência o prompt do Anaconda3) usando o comando:
- streamlit run DeployProjetoAirbnb.py

<p>Para fazer testes você pode usar os dados que estão no documento "Dados para teste.txt" para ter uma base de como funciona e depois ir alterando os valores.</p>

Tenha em mente que por ser uma análise de dados, pode ser que demore alguns minutos para que ele faça a previsão do preço. Ele inclusive, depende do seu computador para rodar a previsão, então quanto pior o computador mais tempo levará.