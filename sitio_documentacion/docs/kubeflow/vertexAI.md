```
Las tuberías de ML están diseñadas para ser fácilmente transportables y pueden escalar sin esfuerzo utilizando contenedores.
```


## VERTEX AI 

- Unicamente se pueden correr el google cloud

## PASOS DE UN PIPELINE

1. preprocesamiento de los datos
2. entrenar tu modelo de aprendizaje automático.
3. ajustar los hiperparámetros en función de algún conjunto de datos de prueba
4. utilizarás ese modelo de aprendizaje automático para realizar alguna predicción y obtendrás esa predicción, la compararás con métricas de prueba para calcular, por ejemplo, precisión o exactitud en un problema de clasificación.


¿cuáles son los pasos típicos en una tubería?

Primero, quieres ingresar los datos.

Este paso inicial se encarga de cargar los datos de entrenamiento en la tubería, haciéndolos accesibles para su posterior procesamiento.

Luego, preprocesarás los datos.

El siguiente paso en la tubería se centra en el preprocesamiento de los datos de entrenamiento que se ingresaron en el paso anterior.

Este paso de preprocesamiento prepara los datos para las etapas posteriores y a menudo tendrá operaciones más específicas del dominio en el que estás trabajando.

Por ejemplo, completar datos faltantes o calcular algún promedio o realizar ingeniería de características.

Después de eso, llega el momento de entrenar el modelo.

Este es el paso crucial que utiliza los datos de entrenamiento preprocesados para entrenar realmente el modelo.

Aquí, los datos pasan por una variedad de algoritmos de entrenamiento para aprender y generar un modelo predictivo.

Una vez que el modelo está entrenado, llega el momento de evaluar el modelo.

Este paso evaluará su rendimiento y calidad.

Aquí se emplean diversas métricas y técnicas para evaluar qué tan bien se desempeña el modelo en datos no vistos, especialmente si estás realizando un tipo de tarea que tiene métricas claras que deseas comparar.

Y esto depende si estás realizando algo como regresión o clasificación.

Una vez que estés satisfecho con el modelo, llega el momento de implementarlo.

Este paso se encarga de implementar el modelo entrenado, poniéndolo a disposición para realizar predicciones o servir propósitos específicos dentro de una aplicación o sistema.