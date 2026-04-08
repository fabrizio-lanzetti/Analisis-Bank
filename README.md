# Análisis Bank — EDA de campañas de marketing bancario

Este repositorio contiene un análisis exploratorio de datos (EDA) sobre campañas de marketing directo (llamadas telefónicas) en una institución bancaria portuguesa. El objetivo es entender patrones de suscripción al depósito a plazo, variables relevantes y preparar el terreno para futuras etapas de feature engineering y modelado.

- Notebooks principales:
  - `analisis_bank.ipynb`: análisis y visualizaciones principales
  - `eda_bank.ipynb`: EDA complementaria
- Dataset: Bank Marketing (UCI Machine Learning Repository)

## Dataset

Los datos provienen del conjunto “Bank Marketing” (campañas de marketing telefónico). Incluye información de cliente (edad, trabajo, educación, préstamos), del último contacto (mes, día de la semana, duración) y de campañas anteriores (número de contactos, días desde último contacto, resultado previo).

- Fuente original (UCI): `https://archive.ics.uci.edu/ml/datasets/Bank+Marketing`
- Columnas destacadas (ejemplos):
  - Cliente: `age`, `job`, `marital`, `education`, `default`, `housing`, `loan`
  - Último contacto: `contact`, `month`, `day_of_week`, `duration`
  - Historial campañas: `campaign`, `pdays`, `previous`, `poutcome`
  - Macroeconómicas: `emp.var.rate`, `cons.price.idx`, `euribor3m`, etc.
  - Objetivo: `y` (suscripción a depósito a plazo: yes/no)

Nota: En `analisis_bank.ipynb` se carga el CSV desde Google Drive. Para ejecución local, descargá el CSV desde UCI y ajustá la ruta.

## Estructura del repositorio
