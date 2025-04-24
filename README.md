Random Forest para Qualidade do Vinho
Este projeto aplica o algoritmo de Random Forest para prever a qualidade dos vinhos com base em suas características físico-químicas. Trata-se de uma tarefa de classificação multiclasse.

Objetivo
Prever a nota (qualidade) de vinhos com base em atributos como acidez, teor alcoólico, cloretos, entre outros, utilizando um modelo de aprendizado de máquina supervisionado.

Tecnologias Utilizadas

Python
Pandas
Scikit-learn
Matplotlib
Seaborn

Etapas do Projeto
1. Importação e Visualização dos Dados
Os dados são carregados via pandas e analisados visualmente usando histogramas, heatmaps e estatísticas descritivas.

2. Preparo dos Dados
Verificação de dados ausentes
Análise de distribuição da variável alvo (qualidade)
Divisão entre conjuntos de treino e teste (80/20)

3. Treinamento do Modelo
Um classificador RandomForest é treinado com o conjunto de treino. Os hiperparâmetros podem ser otimizados usando RandomizedSearchCV.

4. Avaliação do Modelo
Acurácia
Matriz de confusão
Relatório de classificação (precision, recall, f1-score)

5. Visualização de Importância das Variáveis
Gera-se um gráfico de barras com as features mais relevantes para a classificação.

Como Executar
Clone o repositório ou baixe o notebook RandomForest dos vinhos.ipynb
Instale os requisitos:
pip install pandas scikit-learn matplotlib seaborn
Execute o notebook em um ambiente como Jupyter Notebook, VS Code ou Google Colab

Conclusão
O modelo Random Forest se mostrou eficaz para prever a qualidade dos vinhos, com boa acurácia e interpretabilidade das variáveis. O projeto também permite exploração de melhorias com otimização de hiperparâmetros ou engenharia de atributos.

