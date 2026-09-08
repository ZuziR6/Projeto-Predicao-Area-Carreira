# 🎯 Predição de Área de Carreira com Machine Learning

Projeto de **Machine Learning** desenvolvido em Python com o objetivo de prever a **área de carreira mais provável para um estudante** com base em características comportamentais e de perfil.

O projeto foi desenvolvido no **Google Colab**, passando por todas as principais etapas de um fluxo de Machine Learning, desde a preparação dos dados até a criação de uma função capaz de realizar previsões para novos estudantes.

## 🚀 Objetivos

* Explorar a relação entre características comportamentais e áreas de carreira;
* Realizar análise e preparação de dados;
* Treinar e otimizar um modelo de classificação;
* Avaliar o desempenho do modelo;
* Criar uma função para realizar previsões com novos dados.

## 🔎 Etapas do Projeto

### 1. Coleta e integração dos dados

* Utilização de múltiplos datasets;
* Integração das diferentes fontes de dados;
* Organização das variáveis utilizadas no modelo.

### 2. Análise Exploratória de Dados (EDA)

Foram realizadas análises para compreender a distribuição e o comportamento dos dados, incluindo:

* Boxplots;
* Heatmap de correlação;
* Análise das variáveis;
* Identificação de possíveis inconsistências.

### 3. Tratamento dos dados

* Remoção de valores nulos;
* Remoção de registros duplicados;
* Codificação de variáveis categóricas utilizando `LabelEncoder`;
* Preparação dos dados para o treinamento.

### 4. Balanceamento das classes

Foi utilizado o **RandomUnderSampler**, buscando reduzir o desbalanceamento entre as classes da variável alvo.

### 5. Treinamento e otimização

O algoritmo escolhido para classificação foi o **Decision Tree (Árvore de Decisão)**.

Para encontrar uma configuração mais adequada para o modelo, foi utilizado o **GridSearchCV**, realizando uma busca sistemática pelos melhores hiperparâmetros.

### 6. Avaliação

O modelo foi avaliado utilizando:

* Classification Report;
* Matriz de Confusão;
* Validação estratificada entre treino e teste.

## 🤖 Aplicação do Modelo

Além do treinamento e avaliação, o projeto conta com uma função capaz de receber as características comportamentais de um novo estudante e retornar uma **previsão da área de carreira**.

Essa etapa simula uma possível aplicação prática do modelo em um cenário de orientação e análise de perfil profissional.

## 🛠️ Tecnologias

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Imbalanced-learn

## 📂 Estrutura

```text
📦 projeto
 ├── 📓 notebook.ipynb
 ├── 📊 datasets/
 └── 📄 README.md
```

## 🔗 Links

**Notebook no Google Colab:**
https://lnkd.in/dwsZi5JN

**Datasets utilizados:**

* https://lnkd.in/dwKcyWgg
* https://lnkd.in/dRaQYkwY

---

## 📌 Aprendizados

Este projeto permitiu aplicar, na prática, conceitos importantes de **Análise de Dados e Machine Learning**, incluindo preparação de dados, análise exploratória, balanceamento de classes, treinamento, otimização de hiperparâmetros e avaliação de modelos de classificação.
