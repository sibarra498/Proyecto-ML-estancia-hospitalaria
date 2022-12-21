## Proyecto ML estancia-hospitalaria

El siguiente es un proyecto de machine learning, el cual tiene como objetivo predecir si un paciente tendrá una estancia hospitalaria prolongada o no, utilizando la información contenida en el dataset asociado (hospitalizaciones_train.csv y hospitalizaciones_test.csv), la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital.

Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado más de 8 días. Por lo que se debe generar dicha variable categórica y luego categorizar los pacientes según las variables que usted considere necesarias, justificando dicha elección.

El código esta en un script Jupyter Notebook "Eda2.ipynb". En el cual primeramente se realizo un analisis exploratorio de datos y feature engineerging, además de un procesamiento de datos. En donde, posteriormente se usaron 2 modelos para realizar las predicciones, por un lado una regresión logistica y por otro un arbol de decisión. Finalmente mediante el uso de pipelines, se evaluo el modelo mas óptimo para la predicción de la estancia de los pacientes en el centro de salud.

Adicionalmente como método de evaluación del desempeño del modelo, se utilizo la métrica de Exhaustividad (Recall) para las estadías hospitalarias largas, a partir de la matriz de confusión (Confusion Matrix). Tambien se hizo uso de una métrica adicional para verificar el desempeño de su modelo, la metrica de precisión (Accuracy) para las estadías hospitalarias largas.

