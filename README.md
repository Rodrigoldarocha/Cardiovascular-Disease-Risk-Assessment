# 🫀 Cardiovascular Disease Risk Assessment

Projeto de **Ciência de Dados aplicado à área da saúde**, desenvolvido com foco em **análise exploratória, tratamento de dados clínicos e modelagem preditiva** para avaliação do risco de doenças cardiovasculares.

---

## 📌 Visão Geral

Doenças cardiovasculares estão entre as principais causas de mortalidade no mundo. Este projeto utiliza um dataset clínico real do Kaggle para **analisar fatores de risco** e **construir um modelo de Machine Learning** capaz de classificar indivíduos em diferentes níveis de risco cardiovascular.

O projeto foi desenvolvido com **finalidade educacional e de portfólio**, seguindo boas práticas utilizadas em ambientes profissionais.

---

## 🎯 Objetivos do Projeto

* Realizar uma **análise exploratória completa (EDA)** em dados clínicos
* Tratar valores ausentes e inconsistências
* Explorar relações estatísticas entre variáveis
* Construir um **modelo preditivo de classificação**
* Interpretar resultados com base em conhecimento de domínio (saúde)

---

## 🗂️ Dataset

* **Fonte:** Kaggle
* **Nome:** Cardiovascular Disease Risk Assessment Dataset
* **Link:** [https://www.kaggle.com/datasets/ahmeduzaki/cardiovascular-disease-risk-assessment-dataset](https://www.kaggle.com/datasets/ahmeduzaki/cardiovascular-disease-risk-assessment-dataset)

### 📊 Características

* Registros clínicos e demográficos
* Variáveis numéricas e categóricas
* Variável alvo multiclasse: **`CVD Risk Level`**

Exemplos de variáveis:

* Idade
* IMC (BMI)
* Pressão arterial
* Colesterol
* Circunferência abdominal
* Hábitos de vida

---

## 🧪 Metodologia

O projeto segue o fluxo clássico de Ciência de Dados:

1. Download e carregamento dos dados (kagglehub)
2. Exploração inicial e entendimento do dataset
3. Tratamento de valores ausentes
4. Análise Exploratória de Dados (EDA)
5. Pré-processamento e codificação de variáveis
6. Análise estatística e correlação
7. Modelagem preditiva
8. Avaliação e interpretação dos resultados

---

## 🤖 Modelo Utilizado

### Random Forest Classifier

**Motivos da escolha:**

* Excelente desempenho em dados tabulares
* Capacidade de capturar relações não lineares
* Robustez a ruído e outliers (comuns em dados clínicos)
* Permite interpretação via importância das variáveis

---

## 📈 Avaliação do Modelo

Foram utilizadas métricas clássicas de classificação:

* Precision
* Recall
* F1-score
* Matriz de confusão

A avaliação foi realizada em um conjunto de teste separado, garantindo uma análise justa do desempenho do modelo.

---

## 🔍 Principais Insights

* Idade, IMC e pressão arterial são fatores fortemente associados ao risco cardiovascular
* O modelo apresentou desempenho consistente entre as classes
* Os resultados estão alinhados com evidências médicas conhecidas

---

## 🛠️ Tecnologias Utilizadas

* Python 3
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* KaggleHub

---

## 📂 Estrutura do Repositório

```
├── README.md
├── Avaliação_de_Risco_de_Doenças_Cardiovasculares.ipynb
```

---

## 🚀 Próximos Passos

* Comparar com outros modelos (Logistic Regression, XGBoost)
* Ajuste de hiperparâmetros (GridSearchCV)
* Criação de dashboard interativo (Streamlit)
* Comunicação dos resultados para público não técnico

---

## ⚠️ Aviso

Este projeto tem caráter **educacional** e **não substitui diagnóstico médico profissional**.

---

## 👨‍💻 Autor

**Rodrigo Rocha** — [GitHub](https://github.com/Rodrigoldarocha) · [LinkedIn](https://www.linkedin.com/in/rodrigo-rocha-19249170/)
