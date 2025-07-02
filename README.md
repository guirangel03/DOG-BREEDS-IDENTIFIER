# DOG-BREEDS-IDENTIFIER
Exploring the dataset Oxford IIIT Dogs with 3 classification ML algorithims

Como projeto final da disciplina Inteligência Artificial, este trabalho servirá como consolidações de conceitos teoricos e implementação prática relativas ao Machine Learning.

Etapas de execução:
#Preparação
-Importar o dataset localizado no kaggle https://www.kaggle.com/datasets/imbikramsaha/dog-breeds/code;
-Importar e instalar bibliotecas necessárias;
-Localizar diretório de arquivos;
-Carregar o dataset;
-Extrair features das imagens do dataset(CNN embedding);
-Fazer a normalização, requerida pelo SVM;
-Codificar variáveis categoricamente, definir ID de 0 a 24 para as 25 imagens;
-Exploração e análise de dados prévia;

#Implementação dos 3 algoritmos
-Splitting, divisão do dataset;
-Cross-validation para avaliar melhores hiperparâmetros;
-Treinar o modelo com estes hiperparâmetros ideais;
-Prever resultados com base no aprendizado;
-Plotar matriz de confusão a fim de analisar previsto X realizado em cada categoria;
-Calcular e comparar métricas de desempeno entre os 3 algoritmos(Acurácia, F1-Score, RMSE, MAE);

#Redução de dimensionalidade
-Tratar o algoritmo mais bem-sucedido;
-Aplicar LDA para redução de dimensionalidade no SVM;
-Repetir modelo de implementação do algoritmo;
-Comparar métricas do modelo original e com LDA;


CONFIRA O CÓDIGO NO COLAB:
https://colab.research.google.com/drive/1ZJxqJSm9RNwg5AyJsMkFRlE7W0Bs2vpo?usp=sharing
