# Análisis Exploratorio de Datos y Clasificación con Machine Learning

## Objetivos:
- Realizar un análisis exploratorio con los datos proporcionados.
- Entrenar un modelo de machine learning para clasificar los datos faltantes en la columna 'etiqueta'.
- Generar un informe completo que resuma los resultados y conclusiones.

## Descripción:
Este proyecto aborda la exploración de datos, modelado predictivo y clasificación de datos faltantes en una columna específica ('etiqueta'). Se realiza un análisis exploratorio de los datos seguido de la implementación de un modelo de machine learning para clasificar los registros que carecen de etiqueta.

##Resultados
Resulta interesante la precision del modelo Logistico, pues fue de aproximadamente 0.5, es decir que acierta en la mitad de las predicciones, podriamos realicionar esta prediccion con el azar. Despues de buscar un modelo en el que la precision aumente, nos tomamos con Random Forest, del 
paquete scikit-learn, en el cual con el uso de una semilla aleatoria se obtuvo una precision por encima del 90%. De esta manera se cumple con el objetivo del taller, pues los 100 datos faltantes podran ser predecidos con una taza de acierto muy alta, asi la mision se cumple con exito
(Imagenes que contienen la precision de cada modelo pueden ser encontradas en la carpeta de imagenes en la rama Main)

##Conclusiones
Este proyecto de exploración de datos y clasificación de etiquetas faltantes ha arrojado resultados significativos que merecen ser destacados. A continuación, se presentan las conclusiones clave obtenidas durante el desarrollo de este trabajo:

Precisiones de los Modelos:
Modelo Logístico:

La precisión del modelo logístico resultó ser aproximadamente del 50%, lo que indica un rendimiento similar al azar. Este resultado sugiere que el modelo logístico no fue capaz de capturar patrones complejos en los datos o que la relación entre las características y la etiqueta es más intrincada de lo que el modelo puede manejar.
Random Forest:

Tras explorar diversas alternativas, el modelo Random Forest, implementado con el paquete scikit-learn y utilizando una semilla aleatoria, logró una precisión superior al 90%. Este resultado es especialmente alentador, ya que demuestra la capacidad del modelo para realizar predicciones con una tasa de acierto significativamente alta.
Cumplimiento de Objetivos:
El objetivo inicial del taller se centraba en clasificar los 100 datos faltantes en la columna 'etiqueta' con una alta precisión. El modelo Random Forest ha demostrado ser efectivo para lograr este propósito, cumpliendo con éxito el objetivo establecido.
Comparación entre Modelos:
La comparación entre el modelo logístico y Random Forest resalta la importancia de seleccionar cuidadosamente el algoritmo de machine learning. Mientras que el primero mostró limitaciones en la capacidad predictiva, el segundo proporcionó resultados sustancialmente mejores.
Consideraciones Finales:
La elección de Random Forest como modelo final se basó en su rendimiento superior y en la capacidad de manejar relaciones más complejas en los datos. Esta decisión se respalda no solo en la precisión alcanzada, sino también en la robustez del modelo ante conjuntos de datos más desafiantes.

Las imágenes que contienen las métricas de precisión de cada modelo se encuentran disponibles en la carpeta de imágenes en la rama principal (Main), proporcionando una visualización adicional de los resultados obtenidos.

En resumen, este proyecto no solo ha permitido abordar la tarea de clasificación de datos faltantes de manera efectiva, sino que también ha destacado la importancia de seleccionar y evaluar exhaustivamente los modelos de machine learning para garantizar resultados confiables y precisos. El éxito alcanzado en este proyecto sienta las bases para futuras aplicaciones y mejoras en el análisis de datos y la toma de decisiones.


## Instrucciones de Uso:
1. Abre y ejecuta los notebooks con extensión .ipynb para visualizar los datos y modelo empleados. POR FAVOR: antes de correr el codigo sube la base de datos datos_sensores encontrada en el menú
3. Encuentra las predicciones en el archivo predicciones.csv.

## Nota:
- La columna 'etiqueta' solo tiene dos valores posibles: 'Positivo' o 'Negativo'.
