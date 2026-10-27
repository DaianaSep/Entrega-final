# Entrega Final — Daiana Sepúlveda

Notebook integral de ciencia de datos sobre detección de burnout alto en desarrolladores. Continúa el dataset y el enfoque de las pre-entregas, integrando limpieza, EDA, preparación, comparación de modelos y conclusiones de negocio.

## Abrir y ejecutar

- [Ver el notebook en GitHub](https://github.com/DaianaSep/Entrega-final/blob/main/Sepulveda_Daiana_Entrega_Final.ipynb)
- [Abrir en Google Colab](https://colab.research.google.com/github/DaianaSep/Entrega-final/blob/main/Sepulveda_Daiana_Entrega_Final.ipynb)

En Colab, ejecutar todas las celdas en orden. La carga usa el CSV local cuando está disponible y una URL de una versión fija del archivo original cuando no lo está. No es necesario montar Drive.

Para ejecutar localmente: usar Python 3.9 o superior, instalar `requirements.txt` y abrir el archivo `.ipynb` con Jupyter. El CSV adjunto permite trabajar sin descargar el dataset.

## Contenido

1. Definición del problema y carga.
2. Limpieza con auditoría de exclusiones y EDA del entrenamiento.
3. Imputación, escalado y codificación categórica dentro de pipelines.
4. Validación cruzada de cinco particiones, selección por F1 y evaluación en prueba reservada.
5. Conclusiones, recomendaciones y limitaciones.

Se comparan una referencia mayoritaria, regresión logística y Random Forest. Se reserva el 20 % para prueba y se fija la semilla en 42. El dataset carece de documentación de origen y de construcción de etiquetas, por lo que el resultado se presenta como un ejercicio académico y requiere validación externa.
