# Árvores de Regressão – Previsão de Valor de Imóveis (California Housing)

Este projeto faz parte de um exercício do curso de Ciência de Dados. O objetivo é utilizar **árvores de regressão** para prever o valor mediano de imóveis na Califórnia (`median_house_value`) com base em variáveis socioeconômicas e características das casas.

## Etapas do projeto

* Carregamento e preparação da base de dados
* Tratamento de valores ausentes
* Transformação de variáveis categóricas para formato numérico
* Análise de correlação entre as variáveis
* Separação dos dados em treino e teste
* Treinamento de dois modelos de árvore de regressão com profundidades diferentes
* Avaliação dos modelos utilizando **MSE (Mean Squared Error)**
* Visualização gráfica da árvore treinada

## Conclusão

A árvore com **profundidade máxima igual a 8** apresentou melhor desempenho em comparação com a árvore mais simples (profundidade 2), mostrando menor erro tanto na base de treino quanto na base de teste.

A variável **median_income** aparece como uma das mais importantes para prever o valor dos imóveis.

## Ferramentas utilizadas

* Python
* Pandas
* Seaborn
* Matplotlib
* Scikit-learn
