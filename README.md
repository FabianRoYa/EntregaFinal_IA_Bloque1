# EntregaFinal_IA_Bloque1
En este repositorio se recolectan las evidencias del Bloque 1 de la unida de formación Inteligencia artificial avanzada para la ciencia de datos I (Gpo 101).

[Video demostrativo del input de usruario a los modelos.](https://drive.google.com/drive/folders/112iQyrfrXzM40Cu9sH4jqRNaxReGAR5Q?usp=sharing)

# Información del Dataset: Campañas de Marketing Directo de una Institución Bancaria Portuguesa

Este dataset contiene información relacionada con campañas de marketing directo realizadas por una institución bancaria en Portugal. Las campañas se basaron en llamadas telefónicas, donde en muchos casos se contactó más de una vez al mismo cliente para evaluar si este suscribiría (respuesta 'sí') o no ('no') un depósito a plazo.

## Conjuntos de Datos Incluidos

El dataset incluye cuatro versiones distintas:

1. **`bank-additional-full.csv`**
   - Contiene todos los ejemplos (41,188) y 20 variables de entrada.
   - Los datos están ordenados cronológicamente (desde mayo de 2008 hasta noviembre de 2010).
   - Esta versión es muy similar a la utilizada en el análisis de [Moro et al., 2014].

2. **`bank-additional.csv`**
   - Incluye el 10% de los ejemplos de `bank-additional-full.csv` (4,119 registros), seleccionados aleatoriamente.
   - Contiene las mismas 20 variables de entrada.

3. **`bank-full.csv`**
   - Contiene todos los ejemplos (41,188) pero con 17 variables de entrada (una versión anterior del dataset con menos atributos).
   - Los datos también están ordenados cronológicamente.

4. **`bank.csv`**
   - Contiene el 10% de los ejemplos de `bank-full.csv` (4,119 registros), seleccionados aleatoriamente.
   - Incluye las mismas 17 variables de entrada.

### Propósito de las Diferentes Versiones
- Los conjuntos de datos más pequeños (`bank-additional.csv` y `bank.csv`) están diseñados para probar algoritmos de aprendizaje automático que requieren mayor capacidad computacional, como las Máquinas de Vectores de Soporte (SVM).

## Objetivo de Clasificación

El objetivo principal es predecir si un cliente suscribirá o no un depósito a plazo (variable `y`).

## Referencia

[Dataset Original](https://archive.ics.uci.edu/dataset/222/bank+marketing)


