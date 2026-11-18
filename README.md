# Projeto de Estatística Computacional — Coffee Sales

Análise e previsão do faturamento (`daily_sales`, que soma em `monthly_sales`) de uma máquina de venda de café. Unidade de análise: o dia.
Dataset: [Coffee sales (Kaggle)](https://www.kaggle.com/datasets/ihelon/coffee-sales/data).

## Estrutura

```
.
├── data/
│   ├── raw/          # dado original, nunca editado (coffee_sales.csv)
│   ├── interim/      # conjunto diário com variáveis criadas 
│   └── processed/    # train.csv, validation.csv, scaler.joblib 
├── notebooks/
│   ├── 00_teste03_estatistica_descritiva.ipynb          
│   └── 01_estatistica_descritiva_preprocessamento.ipynb # Parte 1 do projeto
├── reports/
│   └── figures/      # gráficos salvos pelos notebooks
├── requirements.txt
└── README.md
```

`interim/` e `processed/` são regenerados ao executar o notebook 01 e não são versionados.

## Como executar

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Abra `notebooks/01_estatistica_descritiva_preprocessamento.ipynb` no VS Code, selecione o kernel da `.venv` e use **Run All**.
O notebook calcula os caminhos a partir da raiz do repositório e funciona rodando da raiz ou de `notebooks/`.

