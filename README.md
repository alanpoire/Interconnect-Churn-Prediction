# Predicción de abandono de clientes — Interconnect

## 1. Descripción del proyecto

Proyecto de clasificación para identificar clientes con riesgo de cancelar sus servicios de telefonía e internet. El objetivo es apoyar la identificación temprana de clientes que podrían abandonar la compañía y facilitar el diseño de estrategias de retención.

## 2. Datos

Se integraron cuatro fuentes de información: contratos, datos personales, servicios de internet y servicios telefónicos.

Los archivos de datos no se incluyen en este repositorio.

## 3. Metodología

- Análisis exploratorio de datos (EDA).
- Limpieza, integración y preparación de datos.
- Ingeniería y selección de características.
- Comparación de modelos de clasificación.
- Optimización de LightGBM y evaluación del desempeño.
- Evaluación mediante F1, AUC-ROC y recall.

## 4. Resultados

El proyecto reportó los siguientes resultados para el modelo optimizado:

| Métrica | Resultado |
|---|---:|
| AUC-ROC | 0.934 |
| F1 | 0.787 |
| Recall | 0.783 |

Estos valores corresponden a los resultados originales reportados en el proyecto y deberán asociarse al modelo y conjunto de evaluación correspondientes.

## 5. Herramientas

Python, Pandas, NumPy, Scikit-learn, LightGBM, Matplotlib y Seaborn.

## 6. Reproducción

1. Clonar el repositorio.
2. Instalar las dependencias indicadas en `requirements.txt`.
3. Colocar los archivos de datos autorizados en la carpeta `data/`.
4. Abrir el notebook `interconnect_churn.ipynb` en Jupyter Notebook o Visual Studio Code.
5. Ejecutar las celdas en orden.

## 7. Conclusión

El proyecto demuestra la aplicación de técnicas de análisis de datos y Machine Learning para abordar un problema de negocio: anticipar la cancelación de servicios y contribuir a la toma de decisiones orientadas a la retención de clientes.