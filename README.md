## Modelo de clasificación de tipos de basura
Este repositorio contiene un modelo de clasificación de tipos de basura utilizando técnicas de aprendizaje automático y redes neuronales convolucionales (CNN). El objetivo del modelo es predecir la clase de basura a la que pertenece una imagen de entrada.

### Datos
El modelo se entrena utilizando un conjunto de datos que consta de más de 50,000 imágenes de basura, separadas en diferentes carpetas según sus clases. El conjunto de datos se divide en directorios de entrenamiento y prueba, y se utiliza una técnica de validación cruzada para evaluar el rendimiento del modelo.

### Arquitectura del modelo
El modelo se basa en una arquitectura de redes neuronales convolucionales (CNN) que ha demostrado ser efectiva en la clasificación de imágenes. La arquitectura incluye varias capas convolucionales, capas de agrupación máxima, una capa completamente conectada y una capa de salida softmax. También se aplica preprocesamiento de imágenes, como escalado y aumento de datos, para mejorar el rendimiento del modelo.

### Entrenamiento y evaluación
El modelo se entrena utilizando el conjunto de datos de entrenamiento y se evalúa en el conjunto de datos de prueba. Durante el entrenamiento, se optimizan los pesos del modelo utilizando el optimizador Adam y se utiliza la pérdida de entropía cruzada categórica como función de pérdida. Se realiza un seguimiento del rendimiento del modelo utilizando métricas como la precisión (accuracy).

### Resultados
Después de entrenar el modelo durante un número determinado de épocas, se obtuvieron los siguientes resultados:

Precisión en el conjunto de entrenamiento: X%
Precisión en el conjunto de prueba: X%

### Uso del modelo
Una vez que el modelo ha sido entrenado y evaluado, se puede utilizar para hacer predicciones de clasificación en nuevas imágenes de basura. Se proporciona un código de ejemplo para realizar predicciones utilizando el modelo entrenado y también para visualizar la matriz de confusión, que muestra cómo el modelo clasifica las diferentes clases de basura.

### Requisitos
Python (version 3.9)
TensorFlow (version 2.12.0)
Keras (version 2.12.0)
scikit-learn (version 1.2.2)
matplotlib (version 0.1.6)
seaborn (version 0.12.2)

### Uso
1. Preparar los datos:
    - Colocar las imágenes de entrenamiento en la carpeta Train/ y las imágenes de prueba en la carpeta Test/.
    - Asegurarse de que las imágenes estén organizadas en subcarpetas según sus clases.
2. Entrenar el modelo:
    - Ejecutar el script de entrenamiento: python train.py
    - Ajustar los hiperparámetros y la arquitectura del modelo según sea necesario.
El modelo entrenado se guardará en el archivo my_model.hdf5.
3. Realizar predicciones:
    - Utilizar el script de predicción: python predict.py ruta_imagen
    - Reemplazar ruta_imagen con la ubicación de la imagen de entrada.
4. Visualizar la matriz de confusión:
    - Ejecutar el script de visualización de la matriz de confusión: python confusion_matrix.py
    - Se generará una matriz de confusión que muestra cómo el modelo clasifica las diferentes clases de basura.
    - La matriz de confusión se visualizará en forma de gráfico y también se mostrarán las métricas de precisión, recall y F1-score para cada clase.
    - Esto proporciona una visión detallada del rendimiento del modelo en la clasificación de las clases de basura.

## Referencias
[Enlace a la biblioteca TensorFlow](https://www.tensorflow.org/resources/libraries-extensions?hl=es-419)
[Enlace a la biblioteca Keras](https://keras.io/api/)
[Enlace a la biblioteca scikit-learn](https://scikit-learn.org/stable/modules/classes.html)
[Enlace a la biblioteca matplotlib](https://matplotlib.org/stable/users/explain/api_interfaces.html)
[Enlace a la biblioteca seaborn](https://seaborn.pydata.org/api.html)

## Autor
Diego Fernández H.

## Contribuciones
Las contribuciones a este proyecto son bienvenidas. Si desea colaborar, lo puedes hacer siguiendo los pasos:
Haz un fork del repositorio.
Crea una rama para tu contribución: git checkout -b mi_contribucion.
Realiza los cambios y realiza commit: git commit -m "Descripción de los cambios".
Haz push a la rama: git push origin mi_contribucion.
Crea un pull request en el repositorio original.
Agradecimientos
Agradecemos a todas las personas que han contribuido y trabajado en este proyecto.
# waste_sorter
