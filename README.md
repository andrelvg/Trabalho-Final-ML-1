# Trabalho-Final-ML-1
Este trabalho busca desenvolver um modelo de machine learning capaz de prever a ocorrência de AVC (Acidente Vascular Cerebral) com base em dados clínicos. A ideia é, com base em indicadores biológicos, criar uma ferramenta que possa indicar possíveis riscos com antecedência.
A base utilizada foi obtida do Kaggle, contendo informações como idade, gênero, hipertensão, doença cardiaca, histórico matrimonial, tipo de trabalho, tipo de residencia, nivel de glicêmico, índice de massa corporal (IMC), se é fumante, além da variável alvo. 
O conjunto é extremamente desbalanceado, a maioria dos registros são de pessoas sem AVC e isto exigiu técnicas apropriadas no pré-processamento e prejudicou um resultado satisfatório do modelo.
O processo envolveu:
- Limpeza e pré-processamento dos dados
- Balanceamento das classes com SMOTE
- Teste de diferentes modelos (KNN, Random Forest, SVM, XGBoost)
- Otimização por GridSearchCV
- Avaliação com métricas como acurácia, recall, F1-score e AUC
Detre todos, o modelo que apresentou melhor desempenho foi o XGBoost, mesmo não tendo sido possível atingir resultado satisfatório para o melhor modelo.
