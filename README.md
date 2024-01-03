### Base de Dados de Apps do GooglePlayStore
Conforme foi exigido fizemos um pre-processamento de uma base de dados. Utilizamos uma base de dados do Kaggle de Apps do Google Play Store. Essa base é dividida em 13 colunas, mas só utilizamos 6, com o objetivo de identificar os Apps favoritos.

Base que utilizamos: https://www.kaggle.com/datasets/lava18/google-play-store-apps

# Projeto de Análise da Play Store

## Descrição
Este projeto utiliza dados tratados da Play Store para realizar análise preditiva usando algoritmos de machine learning, incluindo Naive Bayes e Árvore de Decisão.

## Objetivo
Explorar as métricas da Play Store para prever classificações de aplicativos com base em diversas variáveis, utilizando técnicas de aprendizado de máquina.

## Metodologia
1. **Coleta de Dados:**
   - Dados foram extraídos da Play Store, incluindo informações sobre avaliações, número de downloads, categorias, etc.

2. **Pré-processamento de Dados:**
   - Tratamento de dados ausentes, normalização e codificação de variáveis categóricas foram realizados para preparar os dados para análise.

3. **Análise Exploratória:**
   - Exploração das relações entre diferentes métricas e avaliações de aplicativos.

4. **Modelagem com Naive Bayes:**
   - Implementação do algoritmo Naive Bayes para prever avaliações de aplicativos.

5. **Modelagem com Árvore de Decisão:**
   - Implementação de uma árvore de decisão para comparar o desempenho do modelo com Naive Bayes.

## Resultados
Os modelos foram avaliados quanto à precisão na previsão das avaliações dos aplicativos. Insights obtidos ajudam na compreensão dos fatores que influenciam nas classificações na Play Store.

## Tecnologias Utilizadas
- Python
- Pandas
- Scikit-learn
- Jupyter Notebooks
