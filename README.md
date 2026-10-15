# Semana 8: Implementación y comparación de algoritmos de clasificación en Machine Learning

## 1. Descripción del proyecto

Este proyecto académico tiene como objetivo implementar, evaluar y comparar diferentes algoritmos de clasificación de Machine Learning sobre un mismo conjunto de datos, con el fin de analizar su desempeño e identificar el modelo más adecuado según las métricas obtenidas.

El ejercicio se desarrolla en Python mediante Google Colab y utiliza herramientas de análisis de datos y aprendizaje automático de Scikit-learn.

## 2. Conjunto de datos

Se utiliza el conjunto de datos **Breast Cancer Wisconsin**, disponible en la biblioteca Scikit-learn. Este conjunto contiene características numéricas de muestras de tumores y permite clasificarlas en dos categorías: benigno y maligno.

- **Número de observaciones:** 569.
- **Número de variables predictoras:** 30.
- **Tipo de problema:** clasificación binaria.
- **Variable objetivo:** diagnóstico benigno o maligno.

Este ejercicio tiene fines exclusivamente académicos y no está destinado al diagnóstico médico.

## 3. Algoritmos implementados

Se implementaron los siguientes modelos:

1. Árbol de Decisión (Decision Tree).
2. Bosque Aleatorio (Random Forest).
3. Máquinas de Vectores de Soporte (Support Vector Machine — SVM).
4. K-Vecinos más Cercanos (K-Nearest Neighbors — K-NN).
5. Naive Bayes Gaussiano (Gaussian Naive Bayes).

## 4. Metodología

El desarrollo comprende las siguientes etapas:

- Carga y exploración del conjunto de datos.
- Verificación de valores faltantes.
- Preparación de las variables predictoras y la variable objetivo.
- División de los datos en conjuntos de entrenamiento y prueba, utilizando una proporción de 80 % y 20 %, respectivamente.
- Entrenamiento y evaluación de los cinco algoritmos.
- Comparación de métricas de desempeño.
- Análisis de matrices de confusión.
- Validación cruzada del modelo Random Forest.
- Interpretación de resultados y elaboración de conclusiones.

## 5. Métricas de evaluación

Los modelos se comparan mediante las siguientes métricas:

- Exactitud (Accuracy).
- Precisión (Precision).
- Sensibilidad (Recall).
- Puntuación F1 (F1-score).
- Matriz de confusión.

## 6. Principales resultados

En el conjunto de prueba, Random Forest y SVM obtuvieron los mejores resultados, con una exactitud del 97,37 % y una puntuación F1 del 96,30 %.

Ambos modelos presentaron resultados iguales en las métricas evaluadas. Random Forest se propone como modelo seleccionado debido a la posibilidad de analizar la importancia de las variables predictoras.

Estos resultados corresponden a una evaluación académica sobre el conjunto de datos utilizado y no representan una validación para aplicaciones clínicas.

## 7. Tecnologías utilizadas

- Python.
- Google Colab.
- Pandas.
- NumPy.
- Matplotlib.
- Scikit-learn.
- GitHub.

## 8. Archivos del repositorio

- `Semana_8_Algoritmos_Clasificacion.ipynb`: notebook con el código, el entrenamiento de los modelos, las métricas y el análisis de resultados.
- `Informe_Semana_8_Algoritmos_Clasificacion.pdf`: informe académico con la metodología, los resultados, la discusión y las conclusiones.

## 9. Autor

**Yerson Ronaldo Rivas Ruiz**

Asignatura: Introducción a Machine Learning  
Institución: Universidad de Cundinamarca – CADI  
Actividad: Semana 8 – Algoritmos de clasificación  
Año: 2026

## 10. Referencias

- Scikit-learn. (s. f.). *Breast cancer Wisconsin dataset*. https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html
- Scikit-learn. (s. f.). *Machine learning in Python*. https://scikit-learn.org/stable/
