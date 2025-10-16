# 💧 Análise de Potabilidade da Água Utilizando Técnicas de Machine Learning

Este projeto tem como objetivo avaliar a **qualidade da água** e prever sua **potabilidade** com base em propriedades físico-químicas, utilizando **técnicas de Machine Learning supervisionadas**.  

O estudo utiliza o conjunto de dados **Water Potability Dataset** (Kaggle), que contém milhares de amostras de água coletadas de diferentes fontes, incluindo medições laboratoriais de pH, condutividade, turbidez e presença de compostos químicos.  

---

## 🚀 Objetivos

- Realizar **análise exploratória de dados (EDA)** para identificar padrões que diferenciam águas potáveis e não potáveis.  
- Aplicar algoritmos de **classificação supervisionada** para prever a potabilidade com base nas variáveis químicas.  
- Avaliar o desempenho de modelos de **Machine Learning**, com destaque para o **Random Forest Classifier**.  
- Interpretar os fatores mais relevantes para a qualidade da água e sua relação com a potabilidade.  

---

## 🧠 Metodologia

### 🔹 Pré-processamento dos dados  
- Identificação e tratamento de valores ausentes.  
- Normalização e padronização das variáveis numéricas.  
- Verificação de outliers e análise da distribuição estatística das amostras.  

### 🔹 Análise Exploratória (EDA)  
- Estatísticas descritivas das variáveis físico-químicas.  
- Visualizações com histogramas, boxplots e mapas de correlação.  
- Identificação da proporção de amostras potáveis e não potáveis.  

### 🔹 Modelagem e Avaliação  
- Aplicação do modelo **Random Forest Classifier**.  
- Divisão dos dados em conjuntos de **treino** e **teste**.  
- Avaliação do modelo com métricas de desempenho como **acurácia**, **precisão**, **recall** e **ROC AUC**.  
- Interpretação dos resultados e análise das variáveis de maior impacto.  

---

## 📈 Principais Insights

- Cerca de **39% das amostras** foram classificadas como potáveis.  
- O **pH** e a **condutividade elétrica** da água apresentaram forte correlação com a potabilidade.  
- Nenhum atributo isolado é determinante — a potabilidade depende da **combinação de múltiplos fatores físico-químicos**.  
- O modelo **Random Forest** atingiu **acurácia de aproximadamente 66%**, o que indica desempenho satisfatório considerando a variabilidade natural das amostras.  
- O uso de **Machine Learning** mostrou-se viável para apoiar decisões em **sistemas automatizados de monitoramento da qualidade da água**.  

---

## 🧩 Tecnologias Utilizadas

- **Python**  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Matplotlib  
  - Seaborn  
- **Jupyter Notebook**  
- **Random Forest Classifier**  
- **StandardScaler** e técnicas de pré-processamento de dados  

---

## 📚 Fonte

Dataset: [Water Potability Dataset – Kaggle](https://www.kaggle.com/datasets/adityakadiwal/water-potability)  

---

## 💡 Conclusão

Este projeto demonstra o potencial da **Ciência de Dados** e do **Machine Learning** na análise de questões ambientais e de saúde pública.  
Através da combinação de análise exploratória, pré-processamento e modelagem preditiva, foi possível compreender como variáveis químicas e físicas influenciam a potabilidade da água.  

O trabalho contribui para o desenvolvimento de **ferramentas inteligentes de monitoramento ambiental**, que podem auxiliar na detecção precoce de contaminações e na promoção do acesso à água de qualidade.

---

📘 Projeto desenvolvido para estudos em **Ciência de Dados e Machine Learning**.  
