# 🚀 Data Science & Machine Learning Studies
### Práticas, Algoritmos e Análise de Dados

Este repositório reúne meus estudos e implementações em **Data Analytics** e **Machine Learning**. O objetivo é documentar o aprendizado de diferentes técnicas de modelagem, tratamento de dados e avaliação de métricas em cenários reais.

---

> 📂 **Projetos**

### 1. Análise Multidimensional (Clustering & Classificação)
**Arquivo:** `ML Ops - Clustering, Metrics, CV and Pipelines.ipynb`

Esse notebook contempla a progressão nos meus estudos, sendo estrtutrado em duas frentes:

#### **A. Segmentação de Clientes (Clustering)**
* **Objetivo:** Agrupar perfis de consumo com base em renda anual e score de gastos.
* **Algoritmo:** K-Means.

#### **B. Predição de Risco de Ataque Cardíaco (Classificação)**
* **Objetivo:** Analisar a probabilidade de eventos cardíacos com base em indicadores de saúde.
* **Técnica de Robustez:** Aplicação de **Ruído Gaussiano** (Gaussian Noise) para simular variabilidade nos dados e testar a estabilidade dos modelos.
* **Benchmarking:** Comparação de performance entre os algoritmos **SVM (Support Vector Machine)** e **KNN (K-Nearest Neighbors)** através de Matrizes de Confusão.

#### **C. Definição e análise de indicadores de avaliação**
* **Métricas internas:** Inertia (WCSS), Silhouette Score e Davies-Bouldin Index.
* **Métricas externas:** Adjusted Rand Index (ARI), Normalized Mutual Information (NMI) e Fowlkes-Mallow Index.
* **Ademais:** Cross-validation explanation

### 2. Predição de Sucesso de Pousos (Classificação Supervisionada)
**Arquivo:** `SpaceX-Machine-Learning-Prediction.ipynb`

Este notebook detalha a construção de um pipeline completo de Ciência de Dados para prever o sucesso do pouso do primeiro estágio do foguete Falcon 9, permitindo uma análise estratégica de custos para a "SpaceY".

#### **A. Engenharia de Dados e Análise Exploratória**
* **Objetivo:** Transformar dados brutos extraídos da API da SpaceX em atributos preditivos relevantes.
* **Processamento:** Normalização de dados utilizando **StandardScaler** e aplicação de **One-Hot Encoding** para converter variáveis categóricas (como tipo de órbita e local de lançamento) em formatos numéricos.

#### **B. Modelagem Preditiva de Pousos**
* **Objetivo:** Treinar classificadores para prever a viabilidade de recuperação do foguete (sucesso vs. falha).
* **Técnica de Robustez:** Utilização de **GridSearchCV** para ajuste fino de hiperparâmetros, garantindo a otimização de cada modelo para o conjunto de dados específico.
* **Benchmarking:** Comparação sistemática entre quatro algoritmos fundamentais:
    * **Logistic Regression**
    * **SVM (Support Vector Machine)**
    * **Decision Tree**
    * **KNN (K-Nearest Neighbors)**

#### **C. Definição e Análise de Indicadores de Avaliação**
* **Métricas de Performance:** Avaliação baseada em **Acurácia (Accuracy Score)** nos conjuntos de treino e teste para validar a capacidade de generalização.
* **Validação de Erros:** Implementação de **Matrizes de Confusão** para visualizar o desempenho dos modelos e identificar falsos positivos/negativos.
* **Conclusão:** Os modelos de **Regressão Logística, SVM e KNN** apresentaram a melhor performance (83.33% de acurácia no teste), demonstrando-se superiores à Árvore de Decisão em termos de consistência.

---

> **Áreas de Estudo e Competências**

* **Machine Learning:** Modelagem supervisionada (Classificação) e não-supervisionada (Clustering).
* **Data Analytics:** Análise exploratória de dados (EDA), tratamento de outliers e engenharia de atributos.
* **Data Augmentation:** Uso de técnicas de ruído para aumentar a robustez de modelos preditivos.

---

> **Stack**

* **Linguagem:**
    * Python.
* **Manipulação de Dados:**
    * Pandas;
    * NumPy.
* **Machine Learning:** 
    * Scikit-Learn (KNN, SVM, K-Means, etc..)
* **Visualização & Performance:** * Seaborn
    * Seaborn;
    * Matplotlib;
    * Yellowbrick.

---

<div align="center">
  
##
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/idksizzlr">
          <img src="https://github.com/idksizzlr.png" width="120px;" style="border-radius: 50%;" alt="Vinicius Ferreira Leal"/><br />
          <sub><b>Vinicius Ferreira Leal</b></sub>
        </a>
      </td>
      <td>
        <b>📊 Premium Audit Analyst</b><br>
        Data & Financial analysis. 🚀<br><br>
        <a href="https://linkedin.com/in/viniciusfleal21/">
          <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge">
        </a>
        <a href="mailto:viniciusfleal21@gmail.com">
          <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Badge">
        </a>
        <a href="https://github.com/idksizzlr">
          <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge">
        </a>
      </td>
    </tr>
  </table>

*Obrigado por acompanhar este estudo!*

</div>
