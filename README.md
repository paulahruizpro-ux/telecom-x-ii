# telecom-x-ii
# 📊 Telecom Projeto de Previsão de Churn

## 📌 Sobre o Projeto

Este projeto teve como objetivo desenvolver modelos preditivos para identificar clientes com maior probabilidade de evasão (churn) na empresa Telecom.

A partir de técnicas de pré-processamento, balanceamento de dados e modelagem supervisionada, foram comparados diferentes algoritmos para avaliar desempenho preditivo e capacidade de generalização.

---

## 🎯 Objetivos

* Analisar fatores associados ao churn de clientes
* Tratar desbalanceamento de classes
* Normalizar variáveis quando necessário
* Treinar e comparar modelos de classificação
* Avaliar métricas além da acurácia
* Interpretar importância das variáveis
* Fornecer conclusões e recomendações estratégicas

---

## 🔎 Etapas do Projeto

### 1️⃣ Análise Exploratória (EDA)

* Distribuição da variável alvo (Churn)
* Visualização de variáveis numéricas e categóricas

### 2️⃣ Pré-processamento

* Tratamento de variáveis categóricas (One-Hot Encoding)
* Divisão em treino e teste
* Balanceamento de classes (SMOTE)
* Normalização com `StandardScaler`
* Análise de correlação

⚠️ O balanceamento foi aplicado apenas nos dados de treino para evitar vazamento de dados.

### 3️⃣ Modelagem

Modelos treinados:

* Logistic Regression
* Random Forest

Normalização aplicada para padronizar as variáveis na mesma escala, o que melhora a convergência da Regressão Logística.

---

## 📈 Métricas Avaliadas

Foram utilizadas métricas adequadas para problemas desbalanceados:

* Acurácia
* Precision
* Recall
* F1-Score
* Matriz de Confusão

🔎 O foco principal foi avaliar a capacidade do modelo em identificar corretamente clientes que realmente evadem (classe minoritária).

---

## ⚖️ Overfitting vs Underfitting

Foram analisadas métricas de treino e teste para verificar:

* Overfitting: desempenho muito superior no treino
* Underfitting: desempenho baixo em ambos

A comparação entre modelos permitiu identificar aquele com melhor equilíbrio entre capacidade de generalização e desempenho na classe minoritária(churn).

---

## 🛠️ Tecnologias Utilizadas

* Python 3
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Imbalanced-learn
* Yellowbrick (visualizações)

---

## 🚀 Como Executar

1. Clone o repositório

```bash
git clone <url-do-repositorio>
```

2. Instale as dependências

```bash
pip install -r requirements.txt
```

3. Execute o notebook

```
Telecom_X_2.ipynb
```

---

## 📌 Principais Aprendizados

* Balanceamento deve ser feito apenas no conjunto de treino
* F1-score é essencial quando há foco na classe minoritária

---

## 👩‍💻 Autora

Projeto desenvolvido por Paula Ruiz.

---

## 📄 Licença

Este projeto é para fins acadêmicos e de estudo.
