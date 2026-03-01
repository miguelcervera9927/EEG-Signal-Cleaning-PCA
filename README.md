# EEG-Signal-Cleaning-PCA
Procesamiento de señales EEG mediante Análisis de Componentes Principales (PCA) para la reducción de ruido y detección de focos epileptógenos
# Análisis de EEG y Reducción de Ruido con PCA

Este proyecto aplica técnicas avanzadas de **Matemáticas para Machine Learning** para procesar señales de Electroencefalograma (EEG).

## Objetivo
Utilizar la descomposición en Componentes Principales (PCA) para aislar la señal neurofisiológica relevante de artefactos (ruido), optimizando la detección de anomalías en pacientes con sospecha de epilepsia focal.

## Metodología
- **Cálculo Multivariado:** Optimización de la varianza mediante multiplicadores de Lagrange.
- **Álgebra Lineal:** Descomposición en Eigenvectors y Eigenvalues para rotación de ejes dimensionales.
- **Implementación:** Python (MNE, Scikit-learn, NumPy).

## Resultados
Se logró retener el 95% de la varianza clínica utilizando solo el X% de los componentes originales, eliminando eficazmente el ruido de alta frecuencia.

![Comparación de señal](images/tu_grafica_principal.png)
