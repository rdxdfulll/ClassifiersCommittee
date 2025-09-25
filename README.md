# Comitê de Classificadores | Projeto N1

#### Google Colab: https://colab.research.google.com/drive/1djx2s_zzAdDCwhxLfm3WgwBZnAHMP3Ze?usp=sharing

---
## Grupo:
- Gustavo Henrique Martins
- Ícaro Botelho
- Maria Clara Seixa Scheffel
- Maruan Biasi El Achkar
- Ricardo Falcão Schlieper

### Dataset escolhido: Rain in Australia
- **Detalhado em:** [/dataset](/dataset)
- **Fonte:** https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

### Algoritmos escolhidos:
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier (Tree-Based)
- Random Forest Classifier (Tree-Based)
- XGBoost Classifier (Tree-Based)
- LightGBM Classifier (Tree-Based)
- CatBoost Classifier (Tree-Based)
- Perceptron
- Gaussian Naive Bayes (Naive Bayes)
- Support Vector Classification (SVC)
- Multi-Layer Perceptron (MLPClassifier)
- AdaBoost Classifier (Ensemble Methods)
- Quadratic Discriminant Analysis (QDA)

--------------------
# Relatório Final

<img width="1189" height="590" alt="download (1)" src="https://github.com/user-attachments/assets/de8326ca-e07e-462c-aedd-6032e68793f2" />


### Relatório de Desempenho dos Algoritmos:
| Model                 | Accuracy | Precision | Recall | F1-score |
|------------------------|----------|-----------|--------|----------|
| **LightGBM**              | 0.8646   | 0.7574    | 0.5666 | 0.6483   |
| **CatBoost**              | 0.8633   | 0.7618    | 0.5521 | 0.6402   |
| **Random** Forest         | 0.8600   | 0.7626    | 0.5288 | 0.6245   |
| **SVC**                   | 0.8585   | 0.7865    | 0.4905 | 0.6042   |
| **MLPClassifier**         | 0.8581   | 0.7456    | 0.5400 | 0.6264   |
| **XGBoost**               | 0.8569   | 0.7319    | 0.5525 | 0.6297   |
| **AdaBoost**              | 0.8502   | 0.7252    | 0.5151 | 0.6024   |
| **KNN**                   | 0.8405   | 0.6852    | 0.5099 | 0.5847   |
| **QDA**                   | 0.8381   | 0.6568    | 0.5545 | 0.6014   |
| **Perceptron**            | 0.8298   | 0.6205    | 0.5855 | 0.6025   |
| **Decision Tree**        | 0.7979   | 0.5409    | 0.5453 | 0.5431   |
| **Gaussian Naive Bayes**  | 0.7315   | 0.4374    | 0.7178 | 0.5435   |



### Melhor Algoritmo (baseado na Acurácia):
- **Algoritmo**: LightGBM
- **Acurácia**: 0.8646
- **Precisão**: 0.7574
- **Recall**: 0.5666
- **F1-score**: 0.6483


### Pior Algoritmo (baseado na Acurácia):
- **Algoritmo**: Gaussian Naive Bayes
- **Acurácia**: 0.7315
- **Precisão**: 0.4374
- **Recall**: 0.7178
- **F1-score**: 0.5435


-----------------------------------
## Roteiro de atividades:
**Objetivo:**
- Criar um programa classificador (comitê de Classificadores) com aprendizagem supervisionada e
empregando ao menos 2 (dois) classificadores em um Data Set que possua rótulos verdadeiros da classe.
Deve escolher um Data Set para aplicar a classificação. Após a classificação, deverá comparar os
classificadores para chegar à conclusão de qual algoritmo de aprendizado de máquinas teve o melhor
resultado.

**Algoritmos Sugeridos:**
- KNN    
- Árvores de Decisão       
- Redes Neurais     
- Naive Bayes      
- SVM        
- etc.

**Etapas para documentação:**
- Pesquisar e escolher um Data Set. Estudar o Data Set para conhecer as instâncias, as classes, as
características dos atributos e as quantidades de instâncias e atributos, entre outras informações
pertinentes.

- Definir as informações do Data Set, das Instâncias e dos Atributos. Deve descrever a Base de Dados,
explicando as variáveis, o que cada uma representa, quais os tipos de variáveis.

- Definir qual será a variável target (rótulo da classe) que usará no projeto. Variável target será a
variável de saída, a variável que se deseja “prever” algo, qual será a conclusão que se quer chegar.

- Escolher no mínimo 2 (dois) algoritmos de Machine Learning para criar o comitê de classificadores.

- O documento deve conter os resultados obtidos em cada Classificador. Apresentar as seguintes
métricas: acurácia (taxa de acerto); taxa de erro; matriz de confusão com as métricas Precisão e
Sensibilidade/Recall, F1. Esses resultados devem estar justificados.

- Comparar os resultados do Comitê de Classificadores. Usar um gráfico do tipo Curva ROC
(Receiver Operating Characteristics) para exibir a comparação entre os classificadores.

- A entrega deve ser feita por um link Google Colab (outros formatos devem ser solicitados a priori).
