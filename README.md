# Bitcoin Bot
Esse trabalho foi realizado durante a disciplina de Fundamentos de Ciências de Dados ministrada pelo professor André Carlos Ponce de Leon Ferreira de Carvalho.

## Proposta do trabalho final
Criar um programa que seja capaz de prever a direção do mercado Bitcoin nos próximos dias.

## Como funciona
Os dados do bitcoin foram retirados diretamente da API da [Binance](https://www.binance.com/en/binance-api).

A análise exploratória dos dados foi realizada com o uso de bibliotecas do Python, nós usamos as seguintes bibliotecas: 
1. Binance: para importar os dados da API
2. Datetime: para converter os dados em UNIX para datetime
3. Matplotlib: para plotar os gráficos
4. Json: para ler o arquivo json do Fear and Greed Index
5. Requests: para ler o arquivo do Fear and Greed Index
6. Pandas: manipulação do dataframe
7. TA: análise técnica do dataframe
8. Sklearn: para calcular o R2 score do modelo
9. Prophet: modelo usado para a predição dos preços

## Habilidades exploradas durante o trabalho
* Aquisição dos Dados
* Análise exploratória de dados
* Pre-processamento dos dados
* Modelagem do Trading Bot
* Avaliação dos Resultados

## Perguntas respondidas
* O gráfico de preço da Dogecoin apresentou uma tendência de crescimento maior que a do Bitcoin?
* Existiu correlação entre os preços de fechamento diários das criptomoedas?
* Qual foi a maior alta e baixa das criptomoedas no ano de análise?
* Utilizando o índice de força relativa, quais foram os 10 melhores pontos de compra no ano dessas duas criptomoedas?
