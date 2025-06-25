# Alura_Challenge_Telecom_X

# 📊 Telecom X - Análisis de Evasión de Clientes

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de **Telecom X** con el fin de identificar factores relacionados con la evasión (churn) y ayudar a la empresa a tomar decisiones estratégicas para retener a sus usuarios.

---

## 🧠 Objetivos

- Comprender las causas de la evasión de clientes.
- Analizar las características y comportamientos asociados al churn.
- Proponer insights y recomendaciones estratégicas.
- Servir de base para futuros modelos predictivos.

---

## 🔁 Metodología (ETL + EDA)

### 📌 1. Extracción (Extract)
- Carga de datos desde archivo JSON proporcionado por la empresa.
- Conversión a `pandas.DataFrame` para su análisis.

### 🔧 2. Transformación (Transform)
- Limpieza de columnas: manejo de valores nulos y tipos incorrectos.
- Estandarización de valores ("yes", "no").
- Cálculo de variables nuevas: `GastoDiario`.
- Renombrado de columnas clave para facilitar la lectura.

### 📊 3. Carga y Análisis (Load & Analysis)
- Análisis estadístico básico y visualizaciones.
- Estudio de la distribución del churn según variables categóricas y numéricas.
- Análisis de correlaciones entre factores clave.

---

## 📈 Herramientas utilizadas

- Python 3
- Pandas
- Seaborn y Matplotlib
- Jupyter Notebook

---

## 📝 Principales hallazgos

- Los contratos mensuales tienen tasas de evasión significativamente más altas.
- Los clientes que abandonan tienden a tener menor tiempo como clientes.
- Un mayor gasto mensual también se asocia con una mayor evasión.
- Ciertos métodos de pago están más correlacionados con el churn.

---

## 💡 Recomendaciones

- Incentivar contratos de largo plazo (trimestrales o anuales).
- Enfocar estrategias de fidelización en los primeros meses del cliente.
- Ofrecer descuentos o beneficios a usuarios con alto gasto mensual.

---

## 📁 Archivos del proyecto

- `TelecomX_Analisis_Evasion.ipynb` – Notebook principal con todo el análisis.
- `TelecomX_Data.json` – Fuente de datos utilizada.
- `TelecomX_diccionario.md` – Descripción de las columnas del dataset.
- `README.md` – Descripción general del proyecto.

---

## 🚀 Próximos pasos

- Implementar un modelo de predicción de churn.
- Automatizar el reporte mensual de métricas.
- Crear dashboards interactivos con herramientas como Power BI o Streamlit.
