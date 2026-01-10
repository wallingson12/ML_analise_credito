# 💳 Análise de Crédito com Machine Learning

Este repositório contém um projeto de **classificação de risco de crédito** usando diferentes algoritmos de machine learning. Também são utilizados recursos de interpretabilidade com **SHAP**
---

## 🎯 Objetivo

Desenvolver e comparar modelos de machine learning para prever a aprovação ou não de crédito com base em informações dos clientes, além de interpretar a influência de cada variável nos modelos.

---

## 📁 Dados Utilizados

- Arquivo: `Credit.csv`
- Variável alvo: `class` (aprovado ou não)
- Variáveis preditoras:
  - `checking_status`, `duration`, `credit_history`, `purpose`
  - `credit_amount`, `savings_status`, `employment`, `age`, entre outras

---

## ⚙️ Etapas do Projeto

1. **Pré-processamento**
   - Conversão de variáveis categóricas (`get_dummies`)
   - Normalização (`StandardScaler`)
   - Separação treino/teste

2. **Modelagem**
   - Algoritmos utilizados:
     - Regressão Logística
     - Árvore de Decisão
     - SVM
     - Random Forest
   - Avaliação com métricas:
     - Acurácia
     - Precisão
     - Recall
     - F1-score

3. **Interpretação com SHAP**
   - Análise da importância das variáveis para cada modelo

4. **Rastreamento com MLflow**
   - Registro de métricas e versões de modelos

---

## 🧠 Tecnologias e Bibliotecas

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- shap
- mlflow

---

## 📊 Resultados Esperados

- Comparação de desempenho entre os modelos
- Entendimento de quais variáveis mais influenciam a decisão de crédito
- Registro e reprodutibilidade com MLflow

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/analise-credito.git
   cd analise-credito
