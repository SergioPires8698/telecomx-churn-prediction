# 📊 Telecom X — Previsão de Evasão de Clientes (Churn)

Este projeto tem como objetivo desenvolver modelos de Machine Learning capazes de prever quais clientes possuem maior probabilidade de cancelar seus serviços.

A evasão de clientes (Churn) é um desafio importante para empresas de telecomunicações, pois impacta diretamente a receita e o crescimento do negócio.

---

# 🎯 Objetivo

Construir modelos preditivos que permitam identificar clientes com maior risco de cancelamento e fornecer insights estratégicos para melhorar a retenção de clientes.

---

# 🧠 Etapas do Projeto

O projeto foi desenvolvido em diferentes etapas:

### 1. Preparação dos dados

* Remoção de colunas irrelevantes
* Transformação de variáveis categóricas
* Balanceamento das classes utilizando SMOTE
* Normalização dos dados

### 2. Análise exploratória

* Distribuição da variável churn
* Matriz de correlação
* Análise de variáveis relacionadas à evasão

### 3. Modelagem preditiva

Foram treinados dois modelos de Machine Learning:

* Regressão Logística
* Random Forest

### 4. Avaliação dos modelos

Os modelos foram avaliados utilizando:

* Acurácia
* Precisão
* Recall
* F1-score
* Matriz de confusão

---

# 📊 Principais Insights

A análise indicou que alguns fatores possuem forte influência na evasão de clientes:

* Tipo de contrato
* Tempo de permanência do cliente
* Valor mensal do serviço
* Quantidade de serviços contratados

Clientes com contratos mensais e menor tempo de relacionamento apresentam maior probabilidade de cancelar o serviço.

---

# 📈 Resultado

Entre os modelos avaliados, o **Random Forest apresentou melhor desempenho**, demonstrando maior capacidade de identificar padrões complexos relacionados ao churn.

---

# 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* Scikit-learn
* Seaborn
* Matplotlib
* Google Colab

---

# 🚀 Próximos Passos

* Aplicar modelos mais avançados como XGBoost
* Criar dashboard para visualização dos resultados
* Implementar monitoramento de churn em tempo real
