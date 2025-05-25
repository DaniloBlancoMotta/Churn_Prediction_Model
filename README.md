# Modelo de Predição de Churn de Clientes

[![Python Version](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🎯 Objetivo do Projeto

Este projeto demonstra a construção e avaliação de um modelo de Machine Learning para prever a probabilidade de *churn* (cancelamento) de clientes em um serviço (por exemplo, telecomunicações, SaaS, etc.). O objetivo é identificar proativamente clientes com alto risco de sair, permitindo que a empresa tome ações de retenção direcionadas.

Este repositório serve como um portfólio prático, mostrando habilidades em:

*   Análise Exploratória de Dados (EDA)
*   Pré-processamento de Dados
*   Engenharia de Features
*   Treinamento e Avaliação de Modelos de Classificação (ex: Regressão Logística, Random Forest, Gradient Boosting)
*   Seleção de Métricas Relevantes para Problemas Desbalanceados (ex: Recall, Precision, F1-Score, AUC-ROC)
*   Boas práticas de codificação em Python para Ciência de Dados.

## ✨ Features Principais

*   **Análise Exploratória:** Notebooks detalhados com visualizações para entender os dados.
*   **Pré-processamento:** Scripts para limpeza, tratamento de valores ausentes, encoding de variáveis categóricas e escalonamento.
*   **Modelagem:** Implementação de múltiplos algoritmos de classificação.
*   **Avaliação:** Comparação de performance dos modelos e seleção do melhor.
*   **(Futuro):** API simples (Flask/FastAPI) para servir o modelo treinado.

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3.9+
*   **Bibliotecas Principais:**
    *   Pandas: Manipulação e análise de dados.
    *   NumPy: Computação numérica.
    *   Scikit-learn: Modelagem de Machine Learning, pré-processamento e avaliação.
    *   Matplotlib & Seaborn: Visualização de dados.
    *   Jupyter Notebook: Análise exploratória e prototipagem.
*   **Gerenciamento de Ambiente:** (Opcional: Conda / venv)

## ⚙️ Instalação e Configuração

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/DaniloBlancoMotta/Churn_Prediction_Model.git
    cd Churn_Prediction_Model
    ```

2.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/macOS
    # ou
    venv\Scripts\activate  # Windows
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Como Usar

1.  **Explore os Dados:** Abra e execute os notebooks na pasta `notebooks/` para entender a análise exploratória.
2.  **Execute o Pipeline:** (Instruções a serem adicionadas conforme o código for desenvolvido - ex: `python src/main.py`)
3.  **Visualize os Resultados:** Verifique os relatórios de avaliação e métricas geradas.

*(Nota: Este é um projeto de exemplo. O código e os dados serão adicionados progressivamente.)*

## 📊 Estrutura do Projeto

```
Churn_Prediction_Model/
├── data/             # Dados brutos e processados (ex: .csv)
│   ├── raw/
│   └── processed/
├── notebooks/        # Jupyter notebooks para análise e experimentação
│   └── eda.ipynb
├── src/              # Código fonte principal
│   ├── __init__.py
│   ├── preprocess.py # Módulos de pré-processamento
│   ├── train.py      # Módulo de treinamento do modelo
│   ├── evaluate.py   # Módulo de avaliação
│   └── main.py       # Script principal para executar o pipeline
├── requirements.txt  # Dependências do Python
├── .gitignore        # Arquivos a serem ignorados pelo Git
└── README.md         # Este arquivo
```


