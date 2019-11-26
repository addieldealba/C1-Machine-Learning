## Ejemplo 03

### OBJETIVO

- En este ejemplo veremos como se pueden utilizar algoritmos de K-medias para generar un sistema de recomendaciones basado en una película que hayas visto anteriormente.

#### REQUISITOS

1. Jupyter Notebook, Numpy y SKlearn.
2. La librería creada por nosotros de MLUtilities.py
3. Los datos de películas en CSV.
4. Lo necesario para desarrollar el ejemplo o el Reto

#### DESARROLLO

En este ejemplo demuestro como se puede generar un sistema de recomendación muy similar al que tiene Netflix: "Porque viste tal película, te recomendamos estas otras"...

Para ello, muestro como puedes tomar un dataset y transformarlo en datos numéricos con Dataframes y con mappeos. 
Luego, calculamso los centroides, y con una película obtenemos su centroide mas cercano y lo usamos para obtener todas las películas que pertenecen a ese centroide, haciendo que nos las recomienden.

