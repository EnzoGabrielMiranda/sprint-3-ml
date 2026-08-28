# Modelagem de Machine Learning — Sompo Seguros

Projeto acadêmico do 3º entregável.

## Integrantes

- Gustavo Hideki Ychii — RM 571745
- Enzo Gabriel Lima Miranda — RM 573094

## Objetivo

Prever o `Nivel_Risco` das apólices por meio de modelos de classificação.

## Conteúdo

- preparação dos dados com scaling e One-Hot Encoding;
- holdout estratificado (70% treino e 30% teste);
- Regressão Logística e Random Forest;
- accuracy, precision, recall, F1-score e AUC;
- tuning com GridSearchCV;
- análise da importância das variáveis.

## Como executar

1. Coloque o notebook e a planilha na mesma pasta.
2. Abra `colab` no Google Colab ou Jupyter.
3. Instale, se necessário: `pandas openpyxl scikit-learn matplotlib seaborn`.
4. Execute as células na ordem.

## Resultado resumido

Melhor modelo inicial por F1-score: Regressão Logística. O notebook apresenta os resultados completos e explica as limitações da base.
