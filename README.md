# 🚲 Aluguel de Bicicletas - Previsão com Azure Machine Learning

Este projeto tem como objetivo construir um modelo preditivo para estimar a **demanda por aluguel de bicicletas** com base em dados históricos, utilizando o **Azure Machine Learning**.

---

## 🎯 Objetivo

Desenvolver uma solução prática de Machine Learning que permita prever o número de bicicletas alugadas a partir de variáveis como condições climáticas, data/hora e outros fatores relevantes.

---

## 🧭 Etapas do Projeto

### 1. 📌 Definição do Problema

- Compreensão do desafio: prever a demanda por aluguel de bicicletas
- Identificação das variáveis que influenciam essa demanda

### 2. 📥 Aquisição de Dados

- Coleta de dados históricos de aluguel de bicicletas
- Fontes de dados incluem: data, hora, clima, feriados, entre outros

### 3. 🧹 Pré-processamento de Dados

- Limpeza de dados e remoção de inconsistências
- Tratamento de valores ausentes e **outliers**
- Codificação de variáveis categóricas (One-Hot, Label Encoding)

### 4. 📊 Análise Exploratória de Dados (EDA)

- Visualização de distribuições, correlações e tendências
- Identificação de padrões de comportamento ao longo do tempo

### 5. 🛠️ Seleção e Engenharia de Recursos

- Escolha das variáveis mais relevantes
- Criação de novas features (ex: dia da semana, horário de pico)

### 6. ✂️ Divisão do Conjunto de Dados

- Separação dos dados em:
  - Conjunto de **treinamento**
  - Conjunto de **teste**
- Proporção recomendada: 80/20

### 7. 🧠 Construção do Modelo

- Escolha de algoritmos:
  - Regressão Linear
  - Decision Tree Regressor
  - Random Forest
  - Redes Neurais (caso necessário)
- Treinamento do modelo com os dados históricos

### 8. 📈 Avaliação do Modelo

- Métricas utilizadas:
  - **RMSE** (Root Mean Squared Error)
  - **R²** (Coeficiente de Determinação)
- Verificação de **overfitting** e **underfitting**

### 9. 🛠️ Otimização do Modelo

- Ajuste de hiperparâmetros com técnicas como:
  - Grid Search
  - Random Search
  - Cross Validation

### 10. 🧪 Validação do Modelo

- Teste final com os dados de **validação**
- Avaliação do poder de generalização do modelo

### 11. 🚀 Implantação do Modelo

- Implantação no **Azure ML Endpoint**
- Possibilidade de uso para **previsões em tempo real** via API

### 12. 📝 Documentação e Comunicação

- Relatório técnico com todas as etapas documentadas
- Comunicação clara dos **resultados**, métricas e aprendizados

---

## 🔧 Tecnologias Utilizadas

- Azure Machine Learning
- Python
- Pandas / NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook
