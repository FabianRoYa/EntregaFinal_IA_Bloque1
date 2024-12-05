# EntregaFinal_IA_Bloque1
En este repositorio se recolectan las evidencias del Bloque 1 de la unida de formación Inteligencia artificial avanzada para la ciencia de datos I (Gpo 101).

[Video demostrativo del input de usruario a los modelos.](https://drive.google.com/drive/folders/112iQyrfrXzM40Cu9sH4jqRNaxReGAR5Q?usp=sharing)

#Propósito del Proyecto:

Este proyecto implementa dos algoritmos de clasificación, Random Forest y Regresión Logística, con el objetivo de resolver un problema de clasificación binaria en el mismo conjunto de datos. Cada algoritmo fue diseñado e implementado para cumplir este propósito desde enfoques diferentes, destacando tanto el uso de herramientas avanzadas como la comprensión fundamental de los métodos.

# 1.- Regresión Logística
El modelo de regresión logística fue implementado desde cero, sin el uso de frameworks o bibliotecas especializadas, con el objetivo de explorar y profundizar en los fundamentos matemáticos del algoritmo.

Características principales:
Implementación manual del cálculo de probabilidades mediante la función sigmoide y optimización de los pesos utilizando gradiente descendente.
Transformaciones previas en las características (como normalización) para asegurar un mejor rendimiento del algoritmo.
Evaluación de las métricas estándar de clasificación, como precisión, recall y F1-score, a partir de la salida probabilística generada.
Este modelo fue diseñado para brindar una comprensión conceptual sólida del proceso detrás de la clasificación binaria.

# 2.- Random Forest

El modelo Random Forest se implementó utilizando la biblioteca scikit-learn, aprovechando su capacidad para construir un conjunto de árboles de decisión y obtener predicciones más robustas a partir de su agregación.

Características principales:
Sobremuestreo y submuestreo de los datos usando la técnica SMOTEENN para manejar clases desbalanceadas.
Uso de hiperparámetros configurados para controlar el crecimiento de los árboles y reducir el riesgo de sobreajuste, como max_depth, min_samples_split, y min_samples_leaf.
Generación de métricas como AUC, precisión, recall, y gráficas de desempeño (Curvas ROC y Precision-Recall).

# Información del Dataset: Campañas de Marketing Directo de una Institución Bancaria Portuguesa

El dataset contiene información relacionada con campañas de marketing directo realizadas por una institución bancaria en Portugal. Las campañas se basaron en llamadas telefónicas, donde en muchos casos se contactó más de una vez al mismo cliente para evaluar si este suscribiría (respuesta 'sí') o no ('no') un depósito a plazo.

# Objetivo del Proyecto
El objetivo general de este proyecto es proporcionar dos implementaciones independientes para resolver un problema de clasificación binaria:

- Random Forest, como ejemplo de un modelo avanzado, eficiente y construido con herramientas especializadas.
- Regresión Logística, como un modelo matemáticamente simple, implementado manualmente para un enfoque más didáctico.
Ambos algoritmos están orientados a predecir con la mayor precisión posible la clase de una muestra en un conjunto de datos desbalanceado, utilizando técnicas modernas de preprocesamiento y evaluación.

## Objetivo de Clasificación

El objetivo principal es predecir si un cliente suscribirá o no un depósito a plazo (variable `y`).

# Información Adicional

Este conjunto de datos está relacionado con campañas de marketing directo realizadas por una institución bancaria en Portugal. 

Las campañas de marketing se basaron en llamadas telefónicas, donde a menudo era necesario realizar más de un contacto con el mismo cliente para determinar si suscribiría (`sí`) o no (`no`) un depósito a plazo.

## Contexto del Dataset

- **Propósito:** Evaluar la eficacia de las campañas de marketing telefónicas.
- **Variable objetivo:** Determinar si el cliente suscribirá un depósito a plazo (`sí/no`).

Este dataset proporciona información valiosa para el análisis y la modelización de estrategias de marketing directo y predicción de comportamiento del cliente.




## Referencia

[Dataset Original](https://archive.ics.uci.edu/dataset/222/bank+marketing)


