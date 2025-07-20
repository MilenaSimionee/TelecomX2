# TelecomX2

# 🔍 Análise e Previsão de Churn — Telecom X

Este projeto de Ciência de Dados tem como objetivo **analisar e prever a evasão de clientes (churn)** de uma operadora fictícia chamada Telecom X. O trabalho foi realizado como parte de um desafio prático de classificação, utilizando Python e bibliotecas como pandas, seaborn, matplotlib e scikit-learn.

---

## 📌 Objetivos do Projeto

- Analisar o perfil dos clientes que cancelam o serviço.
- Construir modelos de Machine Learning para prever o churn.
- Avaliar o desempenho dos modelos com métricas apropriadas.
- Fornecer insights estratégicos sobre os fatores que mais influenciam a evasão.

---

## 🧪 Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🧹 Etapas do Projeto

1. **Coleta e Preparação dos Dados**
   - Importação via GitHub
   - Limpeza e tratamento de dados
   - Conversão de variáveis categóricas
   - Normalização dos dados

2. **Análise Exploratória (EDA)**
   - Visualização do comportamento das variáveis
   - Análise de correlação com a variável alvo

3. **Modelagem Preditiva**
   - Separação entre variáveis preditoras (X) e alvo (y)
   - Divisão entre dados de treino e teste
   - Treinamento de 3 modelos:
     - Regressão Logística
     - Árvore de Decisão
     - Random Forest

4. **Avaliação dos Modelos**
   - Matriz de confusão
   - Acurácia, precision, recall, f1-score
   - Comparação entre modelos

5. **Conclusão Estratégica**
   - Interpretação dos resultados
   - Principais fatores relacionados ao churn
   - Sugestões e próximos passos

---

## 📈 Resultados

O modelo com melhor desempenho foi a **Random Forest**, com os seguintes resultados:

- **Acurácia:** 0.80
- **Precision (churn):** 0.69
- **Recall (churn):** 0.45
- **F1-score (churn):** 0.54

---

## 🧠 Conclusão Estratégica

A análise mostrou que variáveis como `tenure`, `MonthlyCharges` e `TotalCharges` estão fortemente relacionadas ao churn. Clientes com menor tempo de contrato e maiores cobranças mensais tendem a cancelar mais.

Recomenda-se que a Telecom X:
- Crie ofertas especiais para clientes no início do contrato;
- Monitore de perto os clientes com alta cobrança mensal;
- Invista em retenção com base nos perfis mais propensos ao churn.

---

## 🔮 Próximos Passos

- Ajustar hiperparâmetros dos modelos com `GridSearchCV`;
- Testar modelos mais robustos como XGBoost;
- Reduzir dimensionalidade com seleção de variáveis;
- Desenvolver um dashboard para uso do time de negócios.

---

## 📂 Estrutura do Projeto

