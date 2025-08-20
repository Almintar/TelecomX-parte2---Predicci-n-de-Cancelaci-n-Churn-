# 📊 Predicción de Cancelación de Clientes

Este proyecto tiene como objetivo analizar los factores que influyen en la cancelación de clientes (churn) en una empresa de telecomunicaciones y construir modelos de Machine Learning que permitan anticipar el abandono de usuarios.

Se aplicaron técnicas de análisis exploratorio, balanceo de datos, normalización y modelado predictivo para comprender las variables más relevantes y proponer estrategias de retención.

# 📂 Estructura del repositorio

<img width="761" height="115" alt="image" src="https://github.com/user-attachments/assets/98d6a0df-4264-415a-91e9-c8ba0d80c752" />

# 🛠️ Metodología

### Carga y limpieza de datos

- Revisión de valores nulos o inconsistentes.
- Eliminación de columnas redundantes.

### Análisis exploratorio (EDA)

- Visualización de la distribución de cancelación (churn).
- Correlación entre variables.
- Relación de variables clave (ej. tiempo de contrato y gasto total) con la cancelación.

### Preprocesamiento

- Normalización de variables numéricas con MinMaxScaler.
- Balanceo de clases usando SMOTE para evitar sesgo hacia la clase mayoritaria.

### Modelado predictivo

- Regresión Logística (requiere normalización).
- Random Forest (no requiere normalización).
- Evaluación de métricas: Exactitud, Precisión, Recall, F1-score y Matriz de confusión.

### Análisis de importancia de variables

- Coeficientes en Regresión Logística.
- Feature importance en Random Forest.

# 📈 Resultados

- Random Forest tuvo el mejor desempeño global en métricas (exactitud y F1-score superiores a la regresión logística).
- Variables como tiempo de contrato y gasto total son factores clave en la predicción de cancelación.
- Se evidenció que los clientes con contratos más cortos y mayor gasto acumulado presentan mayor probabilidad de cancelar.

# 💡 Estrategias de retención propuestas

- Incentivar contratos a largo plazo con beneficios (descuentos, programas de fidelización).
- Identificar clientes con alto gasto y diseñar planes personalizados para evitar su salida.
- Monitorear tempranamente a clientes en riesgo usando el modelo predictivo.

# ✅ Tecnologías utilizadas

Python 3.x
Bibliotecas:
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- imblearn (para SMOTE)
- Jupyter Notebook



