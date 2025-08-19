# TelecomX_parte2

Descripción del Proyecto

Este proyecto tiene como objetivo predecir qué clientes tienen mayor probabilidad de cancelar sus servicios en Telecom X. A partir de esta predicción, se identifican los factores que más influyen en la cancelación y se proponen estrategias de retención de clientes.

Se utilizan técnicas de machine learning, análisis exploratorio de datos y visualización para entregar insights claros y accionables a la empresa.

Estructura del Proyecto

datos_tratados.csv : Dataset con información de clientes, limpio y listo para análisis.

telecomx_parte2.ipynb.ipynb : Notebook principal donde se realiza todo el análisis, desde la preparación de datos hasta la evaluación de modelos.

README.md : Documento de descripción del proyecto y guía para entender el flujo de trabajo.

Metodología

Preparación de los datos

Eliminación de valores nulos en la variable objetivo (tasa_abandono).

Codificación de variables categóricas mediante One-Hot Encoding.

División en conjunto de entrenamiento (70%) y prueba (30%).

Modelado

Regresión Logística: sensible a la escala de los datos; excelente para identificar clientes en riesgo.

Random Forest: modelo basado en árboles; captura relaciones complejas sin necesidad de normalización.

Evaluación de modelos

Métricas utilizadas: Accuracy, Precision, Recall, F1-score, ROC-AUC, matriz de confusión.

Se comparó la capacidad de cada modelo para predecir la cancelación y se identificaron los factores más relevantes.

Análisis de variables

Se evaluó la importancia de cada variable en la predicción.

Factores clave detectados: servicios de streaming, métodos de pago, soporte técnico, tiempo de contrato y protección de dispositivos.

Resultados Clave

La Regresión Logística detecta mejor a los clientes que podrían cancelar (mayor recall).

Random Forest tiene mejor precisión general, pero menor capacidad de identificar clientes de riesgo.

Los factores más influyentes son:

Servicio de streaming de películas.

Métodos de pago electrónicos.

Soporte técnico limitado.

Tiempo de contrato corto.

Protección de dispositivos.

Estrategias de Retención Sugeridas

Focalizar acciones en clientes nuevos o con contratos cortos.

Incentivar el uso de métodos de pago automáticos confiables.

Mejorar y destacar servicios adicionales, como streaming y protección de dispositivos.

Garantizar un soporte técnico eficiente y accesible.

Conclusión

Este análisis permite que Telecom X anticipé la cancelación de clientes y tome decisiones estratégicas para mejorar la retención. Implementar las recomendaciones basadas en los factores identificados puede reducir la pérdida de clientes y aumentar la satisfacción general.

Requisitos

Python 3.8 o superior

Bibliotecas:

pandas

numpy

scikit-learn

imbalanced-learn

seaborn

matplotlib

Instrucciones para ejecutar

Clonar el repositorio.

Asegurarse de tener todas las dependencias instaladas (pip install -r requirements.txt).

Abrir telecomx_parte2.ipynb en Jupyter o Google Colab.

Ejecutar las celdas paso a paso para replicar el análisis, el entrenamiento de modelos y la evaluación.

## Creado por
**Antonio Rojas** – Analista de Machine Learning
