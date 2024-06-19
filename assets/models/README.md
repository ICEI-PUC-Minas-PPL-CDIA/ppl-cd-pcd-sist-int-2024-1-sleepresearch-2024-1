# Modelos do sistema

## Relatório dos Modelos 1 e 2
### Modelo 1:

O Modelo 1 utiliza o algoritmo K-Nearest Neighbors (KNN) para classificar o desempenho acadêmico dos estudantes em 5 classes, com base em 5 variáveis preditoras:

- Qualidade do Sono
- Dores de Cabeça
- Carga de Estudo
- Prática de Atividades Extracurriculares
- Níveis de Estresse
- Após a normalização dos dados e divisão em conjunto de treino (75%) e teste (25%), o modelo KNN foi treinado com diferentes valores de k (número de vizinhos). O valor ideal de k (k=3) foi escolhido com base na menor taxa de erro observada. O modelo final apresentou as seguintes métricas de desempenho no conjunto de teste:

- Acurácia: 98%
- Precisão: 0.98 (média macro)
- Recall: 0.97 (média macro)
- F1-score: 0.98 (média macro)
- A validação cruzada com 5 folds também foi realizada, resultando em uma acurácia média de 98%, o que indica que o modelo generaliza bem para novos dados.

### Modelo 2:

O Modelo 2 utiliza uma Árvore de Decisão para classificar o desempenho acadêmico dos estudantes, utilizando as mesmas 5 variáveis preditoras do Modelo 1. Após a normalização dos dados e divisão em conjunto de treino (75%) e teste (25%), o modelo de Árvore de Decisão foi treinado e apresentou as seguintes métricas de desempenho no conjunto de teste:

- Acurácia: 98%
- Precisão: 0.99 (média macro)
- Recall: 0.97 (média macro)
- F1-score: 0.98 (média macro)
- O modelo de Árvore de Decisão também apresentou um bom desempenho, com métricas semelhantes ao modelo KNN. A visualização da árvore de decisão permite entender as regras de decisão aprendidas pelo modelo.