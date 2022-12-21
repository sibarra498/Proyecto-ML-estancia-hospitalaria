## Proyecto ML estancia-hospitalaria

El siguiente es un proyecto de machine learning, el cual tiene como objetivo predecir si un paciente tendrá una estancia hospitalaria prolongada o no, utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital
Este proyecto tiene como objetivo predecir si un paciente tendrá una estancia hospitalaria prolongada o no, utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados.

Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado más de 8 días. Por lo que debe generar dicha variable categórica y luego categorizar los pacientes según las variables que usted considere necesarias, justificando dicha elección.

El código en un script Jupyter Notebook .ipynb. El cual en primera instancia posee un analisis exploratorio de los datos, feature engineerging, además de un procesamiento de datos. En donde, posteriormente se usan 2 modelos para realizar las predicciones, por un lado se usa una regresión logistica y un arbol de decisión, finalmente mediante el uso de pipelines se evalua cual modelo de ML es más optimo 

Como método de evaluación del desempeño del modelo, se utilizará la métrica de Exhaustividad (Recall) para las estadías hospitalarias largas, a partir de la matriz de confusión (Confusion Matrix).

Como métrica adicional para verificar el desempeño de su modelo, también se utilizará la métrica de precisión (Accuracy) para las estadías hospitalarias largas.

El proyecto se realiza apartir de 2 archivos bases:

1. hospitalizaciones_train.csv': Contiene 410000 registros y 15 dimensiones, el cual incluye la información numérica de la cantidad de días de estancia hospitalaria.

2. hospitalizaciones_test.csv': Contiene 90000 registros y 14 dimensiones, el cual no incluye la información de la cantidad de días de estancia hospitalaria.​


