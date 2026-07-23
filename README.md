# 📊 Avaliação de Risco de Crédito (Credit Score Classification)

Este projeto aplica técnicas de Machine Learning para prever e classificar o perfil de crédito de clientes. O objetivo principal é apoiar a tomada de decisão na concessão de crédito, mitigando os riscos de inadimplência e automatizando a identificação de bons pagadores.

## 🎯 Objetivo do Projeto

Construir um sistema preditivo utilizando o algoritmo **Naive Bayes** capaz de classificar os clientes em três categorias distintas de risco:
*   **High Score** (Baixo risco / Bons pagadores)
*   **Average Score** (Risco moderado)
*   **Low Score** (Alto risco / Potenciais inadimplentes)

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido em **Python**, utilizando as principais bibliotecas do ecossistema de Ciência de Dados:
*   **Pandas:** Para manipulação e tratamento da base de dados.
*   **Scikit-learn:** Para a divisão dos dados, treinamento do modelo (Naive Bayes) e geração das métricas de avaliação.
*   **Imbalanced-learn (SMOTE):** Para tratar o desbalanceamento das classes na base de treino, criando dados sintéticos para a classe minoritária.
*   **Plotly:** Para a visualização interativa dos resultados, como a Matriz de Confusão.

## ⚙️ Estrutura e Etapas do Projeto

1.  **Pré-processamento:** Limpeza dos dados e separação das variáveis independentes (features) da variável alvo (target).
2.  **Separação de Dados:** Divisão da base em conjuntos de Treino e Teste garantindo a proporção original das classes (`stratify`).
3.  **Balanceamento:** Aplicação da técnica de *Oversampling* (SMOTE) exclusivamente nos dados de treino para evitar enviesamento do modelo.
4.  **Treinamento do Modelo:** Aplicação do algoritmo Naive Bayes para aprender os padrões probabilísticos dos clientes.
5.  **Avaliação:** Teste do modelo com dados inéditos e validação de desempenho utilizando métricas como *Accuracy* (Acurácia), *Recall* e *Matriz de Confusão*.
