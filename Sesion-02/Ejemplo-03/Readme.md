## Ejemplo 03

### OBJETIVO 

- Llevaremos en este ejemplo el K-fold cross validation al caso extremo donde hay 1 dato de prueba y todos los demás para entrenamiento. Esto se llama "Leave-One-Out cross validation (LOOCV)

#### REQUISITOS 

1. Jupyter Notebook
2. NumPy
3. SciKit Learn 

#### DESARROLLO

En este ejemplo dividimos los datos en K pruebas, donde K es la cantidad de muestras. Todos los datos se enfocan en ser aprendidos excepto uno, y el último dato se usa para entrenar. Este proceso se repite hasta que todos los datos han sido usados en pruebas. 
