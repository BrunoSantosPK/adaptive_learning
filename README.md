# Adaptive Learning
*Projeto criado para o desafio do Sigma Geek entitulado "O Desafio de Aprendizagem Adaptativa", disponível [aqui](https://sigmageek.com/challenge/the-adaptive-learning-challenge-1659401106436x437495826561630200).*

> IMPORTANTE: Projeto em andamento.

## Objetivo

Dentro de um contexto preparatório de concursos, o treinamento mais comum é por meio de simulados, ou seja, aprendizagem por repetição. Pelo senso comum, quanto mais repetições, maior o aprendizado. Todavia, esta será que é uma afirmação verdadeira? Será que existe uma quantidade de resolução tal qual garante o máximo aprendizado?

Partindo desta provocação, dado um histórico de resolução de questões, como prever a probabilidade de acertar uma nova questão? Esta é a pergunta guia do desafio de aprendizagem adaptativa, que fundamenta o trabalho deste repositório.

## Organização

A primeira parte do estudo está sintetizado dentro do notebook **feature_engineering.ipynb**. Nem todos os campos disponíveis são úteis para carregar como feature em um modelo, principalmente por falta da visão de negócio relacionado ao problema. Neste notebook está descrita a estratégia de maestria, que serve para transformar os dados existentes em uma série histórica e estruturada para os cálculos posteriores.

Dentro da abordagem de maestria, é preciso encontrar as pontuações para cada acerto e bonificação por dificuldade. Esta etapa é executada no notebook **param_tuning.ipynb**, que implementa as diretrizes de um algoritmo genético para encontrar parâmetros apropriados para o cálculo final da maestria.

Por fim, a modelagem final e conclusão do estudo é apresentado no notebook **train_predict.ipynb**, responsável por concluir o ajuste do modelo e as interpretações de resultado.

## Contato

Projeto desenvolvido por Bruno de Lima Santos.<br>
E-mail: bruno.19ls@gmail.com<br>
Linkedin: [Bruno Santos](https://www.linkedin.com/in/bruno-santos/)