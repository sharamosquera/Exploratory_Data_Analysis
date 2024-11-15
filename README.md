# Análisis Exploratorio de Datos (EDA) - Calificaciones de Películas
## Inspección de los Datos
### Estadísticas Descriptivas
#### Para variables numéricas
* IMDB_Rating:
El conjunto de datos contiene 1000 observaciones sobre las calificaciones IMDB. La calificación promedio es 7.95, lo que indica que, en promedio, las películas en este conjunto están bien valoradas. La desviación estándar es de 0.28, lo que sugiere que las calificaciones tienden a ser cercanas a la media, sin una gran variabilidad. La calificación más baja es 7.6, mientras que la calificación más alta es 9.3. La moda de las calificaciones es 7.7, lo que indica que este valor es el más frecuente. El 25% de las calificaciones están por debajo de 7.7, y el 75% están por debajo de 8.1. El coeficiente de variación es de 3.47%, lo que demuestra que hay baja variabilidad en relación con la media. Además, hay una asimetría positiva, lo que sugiere que más películas tienen calificaciones superiores a la media que inferiores. La distribución es relativamente plana, con un valor de curtosis de 1.43.

* Meta_score:
Con 843 observaciones de calificaciones de Meta Score, la calificación promedio es de 77.97, lo que sugiere que, en general, las películas reciben críticas favorables. El 25% de las calificaciones están por debajo de 70, mientras que el 75% están por debajo de 87. La calificación más alta es 100, y la más frecuente es 76. Con una desviación estándar de 12.38, la variabilidad en las calificaciones es moderada. El coeficiente de variación es de 15.87%, lo que indica una variabilidad más significativa en relación con la media. La asimetría es negativa (-0.61), lo que sugiere que hay más películas con calificaciones inferiores a la media. La curtosis es de 0.42, lo que indica que la distribución es relativamente plana.

* No_of_Votes:
Existen 1000 observaciones del número de votos de las películas. El número promedio de votos es de 273,692, con una desviación estándar de 327,372.7, lo que indica una gran variabilidad en los votos. La película con el mayor número de votos tiene 2,343,110, mientras que el número mínimo de votos es 25,088. La mediana es de 138,548 votos, lo que indica que la mitad de las películas tienen más votos que este valor. El coeficiente de variación es de 119.61%, lo que sugiere una gran dispersión en relación con la media. La distribución muestra una fuerte asimetría positiva (2.3), lo que indica que algunas películas tienen una cantidad de votos extremadamente alta. La curtosis es de 6.90, lo que sugiere que la distribución tiene colas pesadas, con muchos valores extremos.

#### Para variables categóricas
* Posters:
En cuanto a los enlaces a los carteles de las películas, se encuentran 1000 valores únicos, lo que indica que cada película tiene un cartel distinto y no hay repeticiones en los enlaces.

* Títulos:
En los títulos de las películas, se observan 999 valores únicos para 1000 observaciones, lo que significa que hay una película que aparece dos veces en el conjunto de datos, denominada "Drishyam".

* Año de lanzamiento:
El conjunto de datos tiene 100 valores únicos en cuanto a los años de lanzamiento. El año más frecuente es 2014, con 32 películas lanzadas en ese año.

* Clasificación por edades:
Existen 16 valores únicos de clasificación por edades. La clasificación más frecuente es "U" (apto para todo público), con 234 películas clasificadas en esta categoría.

* Duración de la película:
La duración de las películas varía en 140 valores únicos. La duración más común es de 100 minutos, con 23 películas que tienen esa duración.

* Género:
Se observan 202 géneros únicos, siendo el género más frecuente el "Drama", con 85 películas clasificadas bajo este género.

* Sinopsis:
Cada película tiene una sinopsis única, con 1000 valores únicos.

* Directores:
Se identifican 548 directores únicos en el conjunto de datos. El director más frecuente es Alfred Hitchcock, con 14 películas en su haber.

* Actores principales:
Hay 660 actores principales únicos, siendo Tom Hanks el actor más repetido, con 12 películas en las que ha sido el principal.

* Segundos actores:
Para los segundos actores, se observan 841 valores únicos, con Emma Watson siendo la más frecuente, participando en 7 películas.

* Terceros actores:
En el caso de los terceros actores, se encuentran 891 valores únicos, con Rupert Grint como el más frecuente, con 5 películas.

* Cuartos actores:
Finalmente, se identifican 939 valores únicos para los cuartos actores, con Michael Caine como el más repetido, participando en 4 películas.

* Ganancias netas:
Existen 823 valores únicos de ganancias netas, con un valor más común de 4,360,000, que corresponde a 5 películas.

#### Impacto de Actores Famosos en las Calificaciones
El análisis revela que las películas con actores famosos tienden a recibir calificaciones ligeramente más altas en comparación con las que tienen actores menos conocidos. Esto sugiere que la presencia de un actor famoso puede influir positivamente en la percepción crítica y en la recepción de la película por parte del público.

#### Parejas con Mejor Calificación Promedio
Se observa que algunas combinaciones de actor y director tienen calificaciones promedio superiores. 

#### Colaboración de Actor y Director
 Las colaboraciones de actores y directores que tienen un historial de películas bien recibidas por la crítica tienden a generar mejores resultados en términos de calificación.

#### Actores Más Apreciados por la Crítica
Se identifican ciertos actores que son consistentemente apreciados por la crítica.

#### Géneros que Generan Más Ingresos
En cuanto a los géneros de películas, los géneros de Acción, Aventura y Ciencia Ficción generan mayores ingresos. 
