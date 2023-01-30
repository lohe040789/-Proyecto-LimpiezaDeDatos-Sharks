


	El objetivo de este proyecto es poder realizar una limpieza de datos, desde eliminar o sustituir valores nulos, poder relacionar las columnas entre si y completar datos faltantes que tengan relación entre ellas y hacer uso de la biblioteca pandas como todo lo aprendido dado en clase. Tratando de que el proceso de limpieza se vaya adecuando a una hipótesis que nos plantearemos para poder comprobarla.
Hipótesis a probar: ¿Son los surfistas los más afectados por el ataque del tiburón blanco?
Pasos con que seguimos la limpieza:
1)Obtenemos los datos de día-mes-año de cada caso posible a través de la columna ‘Case Number’.
2)En la Columna ‘Species’ filtramos los diferentes tipos de tiburones creando una función que nos devolviera solo el nombre de la especia.
3)En la columna actividad ‘Activity’ hicimos los mimos pasos que en ‘Species’ para encontrar la actividad realizada en las cadenas de ‘str’.
4) rellenamos los valores nan con ‘Unknow’.
5)Eliminamos filas con muy poca frecuencia con respecto al total de los datos.
6)Eliminamos todas las filas donde los datos eran totalmente ‘Nan’.
7)Realizamos una gráfica donde podemos comprobar que los Tiburones blancos atacan más a los buzos que a los surfistas.

