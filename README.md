# Comparación de Capas Convolucionales Normales y Separables Profundas

## Descripción

Este proyecto analiza el impacto del uso de **convoluciones normales** y **convoluciones separables en profundidad** en redes neuronales convolucionales (CNN). Se evalúan métricas clave como el **número de parámetros**, el **tiempo de entrenamiento** y el **rendimiento en clasificación de imágenes**.

Las convoluciones separables han demostrado reducir la cantidad de parámetros sin comprometer el rendimiento en ciertas arquitecturas, lo que las hace atractivas para modelos eficientes. Este estudio busca cuantificar estos efectos mediante experimentos controlados.

## Enfoque

Se implementaron y compararon dos arquitecturas de CNN:  
1. **Modelo con convoluciones normales**  
2. **Modelo con convoluciones separables en profundidad**  

Cada modelo fue entrenado y evaluado utilizando técnicas de optimización de hiperparámetros con **Optuna**. Los experimentos incluyen métricas como precisión, pérdida y tiempos de ejecución.

## Objetivos

1. Comparar el número de parámetros entre ambos tipos de convoluciones.
2. Evaluar el tiempo de entrenamiento requerido para cada arquitectura.
3. Medir el rendimiento en clasificación de imágenes.
4. Determinar si la reducción de parámetros compromete la capacidad de generalización del modelo.

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal.
- **TensorFlow/Keras**: Framework para la construcción y entrenamiento de redes neuronales.
- **Optuna**: Herramienta para la optimización de hiperparámetros.
- **DAGsHub**: Seguimiento y almacenamiento de experimentos.
- **NumPy y Pandas**: Manipulación y análisis de datos.
- **Matplotlib y Seaborn**: Visualización de resultados.

## Temas Involucrados

- **Aprendizaje Profundo**
- **Redes Neuronales Convolucionales**
- **Optimización de Modelos**
- **Ciencia de Datos**

## Estructura del Repositorio

```bash
Comparacion_Capas_Convolucionales_Normales_vs_Separables/
├── Reporte_Final_CNN_vs_Separable.pdf      # Informe con los resultados del experimento
├── Modelos_de_clasificación.ipynb          # Notebook con la implementación y entrenamiento de modelos
├── Predicciones_de_clasificaciones.ipynb   # Evaluación y predicciones finales
├── Copia_de_Modelos_de_clasificación.ipynb # Repetición del entrenamiento en CPU con mayor RAM
├── README.md                                # Este archivo
