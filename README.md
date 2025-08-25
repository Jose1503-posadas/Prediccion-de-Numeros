# Proyecto MNIST - Regresión Logística

Este proyecto implementa un modelo de **regresión logística** para clasificar imágenes del dataset **MNIST**.  
El modelo **predice el número mostrado en cada imagen** basado en el entrenamiento con los datos normalizados y transformados.  


---

## Contenido

- `MNIST` dataset
- Normalización de imágenes
- Transformación de etiquetas (0 → 10)
- Función de visualización `displayData`
- Función de gradiente `lrGradient` y `gradientDescent`
- Función para visualizar predicciones `visualize_predictions`

## Metodología

1. **Carga de datos:** se obtiene el dataset MNIST desde tf.keras.datasets.

2. **Preprocesamiento:** normalización (0-255 → 0-1) y transformación de etiquetas (0 → 10).

3. **Visualización:** se muestran imágenes para explorar los datos.

4. **Entrenamiento:** se implementa la regresión logística con gradiente descendente y regularización.

5. **Predicción:** el modelo identifica el número de cada imagen.

6. **Visualización de resultados:** comparación entre predicción y etiqueta real.

