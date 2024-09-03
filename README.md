# knn_basic
Este repositório contém uma implementação do algoritmo K-Nearest Neighbors (KNN) em Python

Descrição

Este repositório contém uma implementação do algoritmo K-Nearest Neighbors (KNN) em Python. A implementação foi feita de forma didática, sem utilizar bibliotecas externas como NumPy ou Scikit-learn, e tem como objetivo classificar um conjunto de dados com base na proximidade de pontos em um espaço multidimensional usando a distância Euclidiana.

Funcionalidades
Cálculo da Distância Euclidiana:

Implementa a fórmula da distância Euclidiana para calcular a proximidade entre dois pontos em um espaço de N dimensões.
Classificação KNN:

Classifica um conjunto de dados de teste com base em um conjunto de dados de treinamento, identificando os k vizinhos mais próximos e determinando a classe mais frequente entre eles.
Estrutura do Código
distancia_euclidiana(ponto1, ponto2):

Função que calcula a distância Euclidiana entre dois pontos.
knn_classificar(dados_treinamento, dados_teste, dados_originais, k):

Função que classifica os dados de teste com base no conjunto de dados de treinamento utilizando o algoritmo KNN.
Execução:

O valor de k é definido, e o algoritmo KNN é utilizado para classificar os pontos de teste. Os resultados são exibidos no terminal.
