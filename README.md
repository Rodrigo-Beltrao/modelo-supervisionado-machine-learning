# modelo-supervisionado-machine-learning
Resumo do código para a descrição no GitHub:

Este repositório contém um projeto de modelos supervisionados para análise de dados relacionados a habitações, veículos e churn modelling. O código está escrito em Python usando a biblioteca Pandas para manipulação dos dados e as bibliotecas scikit-learn para implementação dos modelos.

A primeira parte do código trata do carregamento dos dados dos arquivos "housing_teste.csv" e "housing_treino.csv" em dataframes de treino e teste. Em seguida, é realizado um modelo de regressão linear para prever a variável "Sale_Price" com base em cinco variáveis independentes.

A métrica MAE (Mean Absolute Error) é apresentada para avaliar a precisão do modelo em relação às previsões. Também é calculado o MAPE (Mean Absolute Percentage Error) para medir a acurácia das previsões.

Na próxima etapa, o código carrega dados do arquivo "mtcars.csv" para um dataframe e executa um modelo de regressão logística para relacionar a variável dependente "VS" (motor com configuração em V ou em linha) com as variáveis independentes "mpg", "cyl", "disp", "hp" e "wt". A acurácia e o F1-Score são apresentados para avaliar o desempenho do modelo.

Em seguida, é aplicado um modelo de árvore de decisão para relacionar as mesmas variáveis do arquivo "mtcars.csv". A acurácia e o F1-Score do modelo final usando a árvore de decisão são apresentados.

Na última parte do código, é carregado o arquivo "Churn_Modelling.csv" para um dataframe e é executado um modelo de redes neurais para relacionar a variável dependente "Exited" com as demais variáveis independentes. São realizados experimentos para encontrar a melhor arquitetura da rede neural que entregue o melhor resultado para a acurácia.

A função de ativação escolhida para o modelo de redes neurais é a função logística, devido à sua suavidade, que facilita a convergência e evita problemas de instabilidade.

A acurácia final do modelo de redes neurais é apresentada para avaliar o desempenho geral do modelo.

Este projeto visa demonstrar a aplicação de modelos de regressão linear, regressão logística, árvore de decisão e redes neurais em diferentes conjuntos de dados e apresentar suas respectivas métricas de avaliação.
