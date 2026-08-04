# DCC127---Mineração-de-Dados

Este repositório contém as atividades e projetos desenvolvidos na disciplina **DCC127 - Mineração de Dados**. O objetivo principal da disciplina é abordar técnicas, algoritmos e estratégias para extração de conhecimento e padrões a partir de conjuntos de dados.

---

## ⛏️ Sobre a Disciplina

A disciplina de Mineração de Dados capacita na análise e modelagem de dados para a resolução de problemas reais de aprendizado estatístico e de máquina. 

O percurso prático da matéria contou com **5 trabalhos desenvolvidos**:
1. **Mapeamento e Definição de Tipos de Problemas:** Estudo teórico/descritivo identificando e caracterizando os principais tipos de tarefas e métodos em Mineração de Dados.
2. **Pré-processamento de Dados:** Prática com limpeza, transformação e adequação de conjuntos de dados.
3. **Agrupamento (Clustering):** Implementação e análise de métodos de aprendizado não supervisionado.
4. **Regras de Associação:** Identificação de padrões de coocorrência e análise de cestas de compras.
5. **Classificação:** Modelagem supervisionada para predição de rótulos e categorias.

---

## Detalhamento dos Tópicos Estudados na Disciplina

Embora os trabalhos práticos tenham focado em problemas específicos, os conteúdos teóricos e práticos abordados ao longo da matéria englobaram as seguintes áreas de conhecimento:

### 1. Visão Geral dos Tipos de Problemas
* **Objetivo:** Compreender o fluxo de descoberta de conhecimento em bases de dados (KDD) e mapear qual técnica utilizar para cada desafio de negócio.
* **Tópicos abordados:**
  * Diferença entre aprendizado supervisionado, não supervisionado e semi-supervisionado.
  * Identificação de cenários para classificação, regressão, agrupamento e associação.

### 2. Pré-processamento de Dados
* **Objetivo:** Tratar e preparar a base de dados para garantir a qualidade e a eficácia dos modelos analíticos.
* **Tópicos abordados:**
  * Limpeza de dados (tratamento de valores ausentes e *outliers*).
  * Normalização, padronização e reescalonamento de atributos.
  * Discretização e codificação de variáveis (*One-Hot Encoding*, *Label Encoding*).
  * Seleção de atributos e redução de dimensionalidade.

### 3. Agrupamento (Clustering)
* **Objetivo:** Agrupar objetos similares em *clusters* sem o uso de rótulos prévios.
* **Tópicos abordados:**
  * Algoritmos de agrupamento (ex: **K-Means**, **DBSCAN**, **Agrupamento Hierárquico**).
  * Funções de distância e métricas de similaridade (Euclidiana, Manhattan, Cosseno).
  * Avaliação da qualidade do agrupamento (*Silhouette Score*, Inércia/SSE).

### 4. Regras de Associação
* **Objetivo:** Descobrir relações ocultas, padrões frequentes e dependências entre itens (*Market Basket Analysis*).
* **Tópicos abordados:**
  * Algoritmos para extração de itens frequentes (ex: **Apriori**, **FP-Growth**).
  * Métricas de interesse: **Suporte**, **Confiança** e **Lift**.
  * Filtragem, interpretação e avaliação de regras geradas.

### 5. Regressão
* **Objetivo:** Compreender a construção de modelos para estimativa e previsão de variáveis numéricas contínuas.
* **Tópicos abordados:**
  * Regressão Linear Simples e Múltipla.
  * Métricas de avaliação de desempenho (MSE, RMSE, MAE, R²).
  * Conceitos de ajuste de modelo (*overfitting*, *underfitting* e regularização).

### 6. Classificação
* **Objetivo:** Treinar algoritmos supervisionados para atribuir rótulos ou categorias a novos dados.
* **Tópicos abordados:**
  * Algoritmos de classificação (ex: **Árvores de Decisão**, **KNN**, **Naive Bayes**, **Random Forest**, **SVM**).
  * Divisão de dados (Treino/Teste) e validação cruzada (*Cross-Validation*).
  * Métricas de avaliação: **Matriz de Confusão**, **Acurácia**, **Precisão**, **Recall**, **F1-Score** e **Curva ROC/AUC**.

---

### Pré-requisitos

Certifique-se de ter o **Python 3.x** e o **Jupyter Notebook** (ou VS Code com suporte a `.ipynb`) instalados em sua máquina.

As bibliotecas mais comuns utilizadas nos scripts/notebooks são:
* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib` / `seaborn`
* `outras`
