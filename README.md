# Projeto de Estatística Computacional — Coffee Sales

Análise e previsão do faturamento (`daily_sales`, que soma em `monthly_sales`) de uma máquina de venda de café. Unidade de análise: o dia.
Dataset: [Coffee sales (Kaggle)](https://www.kaggle.com/datasets/ihelon/coffee-sales/data).

## Estrutura

```
.
├── dataset/
│   ├── coffee_sales.csv 
├── notebooks/
│   ├── coffee_sales.ipynb          
├── requirements.txt
└── README.md
```

## Como executar

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Abra `notebooks/01_estatistica_descritiva_preprocessamento.ipynb` no VS Code, selecione o kernel da `.venv` e use **Run All**.
O notebook calcula os caminhos a partir da raiz do repositório e funciona rodando da raiz ou de `notebooks/`.

