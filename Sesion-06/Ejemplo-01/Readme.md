## Ejemplo 01

### OBJETIVO

- Entrenamiento de una neurona artificial para crear una compuerta OR.

#### REQUISITOS

1. Jupyter Notebook
2. NumPy
3. Funciones de la sesión 05

#### DESARROLLO

En este ejemplo vamos a entrenar una neurona artificial para que tenga el comportamiento de una compuerta OR. Para ello, vamos a realizar el algoritmo de retropropagación en una sola neurona. 

El primer paso será inicializar la neurona para que tenga 2 entradas y una salida. Una vez inicializada calculamos el error logístico y calculamos la derivada. Con la derivada, llevamos a cabo el ajuste de pesos sinápticos. repetimos este proceso hasta que el error logístico sea el mínimo posible.