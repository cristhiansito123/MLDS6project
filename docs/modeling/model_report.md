# Reporte del Modelo Final

## Resumen Ejecutivo

Uno de los mayores problemas al tratar de predecir transacciones fraudulentas es la poca cantidad de datos positivos que se tiene, esto hace que la precisión del modelo sea muy compleja ya que no tan solo un falso positivo con la poca cantidad de positivos que hay, disminuye la acertividad del modelo. 
## Descripción del Problema

Se buscó implementar una red neuronal convolucional (CNN) combinada con una red neuronal recurrente (RNN) para predecir de una base de datos cuales transacciones son fraudulentas según características de estas transacciones.

## Descripción del Modelo

La combinación de la parte convolucional y recurrente permite capturar tanto las características locales como las secuenciales de los datos de transacciones, lo que mejora la capacidad del modelo para detectar patrones de fraude en diferentes niveles de granularidad. Es importante destacar que los detalles específicos del modelo pueden variar según la implementación y los requisitos del proyecto.

## Evaluación del Modelo

La evaluación del modelo presentó las siguientes métricas de desempeño:

Exactitud: 0.908410083927954
Precisión: 0.01281398506449423
Recall: 0.8728323699421965
F1-score: 0.025257171531320562

## Conclusiones y Recomendaciones

-Aumentar el tamaño y la diversidad del conjunto de datos de entrenamiento: Esto podría ayudar a que el modelo aprenda patrones más representativos y a reducir el desequilibrio entre las clases de transacciones fraudulentas y legítimas.

-Ajustar los umbrales de clasificación: Experimentar con diferentes umbrales de decisión puede ayudar a equilibrar la precisión y el recall. Ajustar el umbral puede permitir priorizar la reducción de los falsos positivos o los falsos negativos según sea necesario.

-Explorar técnicas de regularización: Las técnicas como la regularización L1 o L2 pueden ayudar a evitar el sobreajuste del modelo y mejorar su capacidad para generalizar a nuevos datos.

-Experimentar con la arquitectura del modelo: Puede ser beneficioso probar diferentes arquitecturas de red neuronal, incluyendo cambios en el número y la disposición de las capas convolucionales y recurrentes, así como el uso de otras capas como capas de dropout para mejorar el rendimiento del modelo.

