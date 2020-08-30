# Información sobre el dataset 
<b><i>Dataset extraido de UCI </i></b>
Este conjunto de datos está relacionado con variantes tintas del vino portugués "Vinho Verde". Para más detalles, consulte la referencia [Cortez et al., 2009]. Debido a cuestiones de privacidad y logística, solo están disponibles las variables fisicoquímicas (entradas) y sensoriales (la salida) (por ejemplo, no hay datos sobre tipos de uva, marca de vino, precio de venta del vino, etc.).

Los conjuntos de datos pueden verse como tareas de clasificación o regresión. Las clases están ordenadas y no equilibradas (por ejemplo, hay vinos mucho más normales que excelentes o malos).

Este conjunto de datos también está disponible en el repositorio de aprendizaje automático de UCI, https://archive.ics.uci.edu/ml/datasets/wine+quality.

Contenido

Para obtener más información, lea [Cortez et al., 2009].
Variables de entrada (basadas en pruebas fisicoquímicas):

1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data):
12 - quality (score between 0 and 10)

Tambien debe cambiar el valor de salida de manera binaria, donde "quality" inferior a 7 está categorizado como 0 (malo) y "quality" mayor a 7 categorizado como 1 (bueno).
