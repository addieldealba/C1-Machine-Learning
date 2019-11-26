## Reto 02

### OBJETIVO

- Segmenta una manzana (Separa la manzana del fondo) 

#### REQUISITOS

1. Jupyter Notebook
2. NumPy
3. OpenCV

#### DESARROLLO

El reto consiste en hacer una binarización por umbral:

1) genera un umbral para que queden valores de 0 para el fondo, y 255 para la manzana.
2) Luego transforma la imagen binarizada a negativo,
3) Transforma los valores 255 a valores 1. 
3) Finalmente multiplica con np.multiply la imagen binarizada (con 0s y 1s) contra los canales, de tal manera que solamente te quedes con la manzana.