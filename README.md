# Modelagem Preditiva para Avaliação de Desempenho Acadêmico

Este projeto visa desenvolver um modelo preditivo capaz de avaliar o desempenho acadêmico de estudantes com base em um conjunto diversificado de variáveis. O processo é dividido em etapas essenciais, fornecendo uma abordagem sistemática para a construção e avaliação do modelo.



## Passos do Projeto


### 1. Aquisição do Dataset
  - Inicialmente, o conjunto de dados é obtido, contendo informações variadas sobre estudantes, incluindo características demográficas, histórico educacional e comportamentos.


### 2. Limpeza de Outliers
  - Realiza-se uma análise estatística para identificar e remover outliers do conjunto de dados. Essa etapa é crucial para garantir que o modelo não seja influenciado por valores atípicos que possam distorcer as previsões.



### 3. Normalização de Valores Numéricos
  - Os valores numéricos presentes no conjunto de dados são normalizados, ajustando-os para uma escala comum. Isso é essencial para algoritmos sensíveis à escala, garantindo uma convergência eficiente e evitando dominância de atributos.



### 4. Encoding de Valores Categóricos
  - Variáveis categóricas são codificadas para representações numéricas, possibilitando a inclusão dessas informações no modelo. O método ordinal encoding é aplicado, considerando a natureza das variáveis.



### 5. Definição da Variável Alvo
  - Identifica-se a variável alvo, que representa o desempenho acadêmico. Esta variável é crucial para o treinamento e avaliação do modelo, sendo o foco principal das previsões.



### 6. Criação de Datasets de Treino e Teste
  - Os dados são divididos em conjuntos de treino e teste. Para uma análise mais abrangente, dois conjuntos de treino e teste são criados: um incluindo um conjunto específico de variáveis e outro adicionando características extras disponíveis. Essa abordagem permite a comparação de desempenho entre os dois cenários distintos.



### 7. Construção da Árvore de Decisão
  - Implementa-se um modelo de árvore de decisão, escolhido devido à sua capacidade de lidar com relações complexas entre variáveis. A árvore é treinada com base nos conjuntos de treino e posteriormente utilizada para realizar previsões sobre o desempenho acadêmico.



### 8. Avaliação dos Resultados
  - Finalmente, avalia-se o desempenho do modelo com métricas relevantes, como acurácia, sensibilidade, especificidade e F1-score. A comparação entre os dois conjuntos de treino/teste permite insights valiosos sobre a influência das características adicionais nas previsões do modelo.



Este projeto proporciona uma abordagem abrangente e estruturada para o desenvolvimento de um modelo preditivo, desde a aquisição e preparação dos dados até a avaliação e interpretação dos resultados.
