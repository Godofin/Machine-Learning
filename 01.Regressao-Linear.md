# Regressão Linear

## O que é Regressão Linear?

A Regressão Linear é um algoritmo de aprendizado de máquina que tem como objetivo encontrar uma relação linear entre os dados de entrada. Em um projeto de ciência de dados, o modelo representa essa relação através de uma linha reta, um plano ou, em dimensões mais altas, um hiperplano, que se ajusta aos dados.

## Qual é o Grande Objetivo?
O objetivo principal é encontrar a "melhor" linha que representa a tendência dos seus dados de treinamento. Essa linha deve estar o mais próximo possível de todos os pontos de dados. Uma vez que essa linha é encontrada, ela pode ser usada para prever o valor de novos dados que o modelo nunca viu.

## Como o Modelo Avalia seu Desempenho?
Para saber se a linha é "boa", o modelo utiliza uma função de erro chamada Erro Quadrático Médio (MSE). Essa função mede a distância entre a linha de previsão e cada um dos pontos de dados reais. O erro é elevado ao quadrado para garantir que todos os valores sejam positivos e para penalizar os erros maiores de forma mais significativa. O objetivo do modelo é minimizar essa função, buscando um MSE o mais próximo de zero possível.

## Como o Modelo Encontra a Solução?
Para encontrar a linha ideal (aquela que minimiza o MSE), o modelo usa um algoritmo de otimização chamado Descida do Gradiente. Pense no erro quadrático médio como uma montanha, e o objetivo é chegar ao ponto mais baixo.

- O modelo começa em um ponto aleatório na montanha.

- Em cada ponto, ele calcula o gradiente, que é a direção de maior inclinação (onde o erro está subindo mais rápido).

- Então, o algoritmo dá um pequeno passo na direção oposta ao gradiente (descendo a montanha).

- Esse processo se repete, ajustando os parâmetros do modelo (w e b) a cada passo, até que o modelo chegue ao ponto mais baixo da montanha, onde o erro é mínimo.

Tudo isso resulta na linha de regressão final, que está balanceada para representar a tendência geral dos dados de treino.
