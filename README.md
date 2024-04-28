# predicciones_ventas_productos_alimenticios
Una proyección de ventas para el area de alimentos de los próximos años

Carga de base y trabajo pre-operativo:

-Para esta primera parte se carga la base en formato csv, luego se importa las librerias necesarias para el trabajo y se da un vistazo general de la base.

Limpieza de DataFrame:

-Primero se verifica si hay nulos, luego si hay duplicados y finalmente se verifica columna por columna para corregir los errores y dejar nuestra base lista para realizar visualizaciones.

Visualizaciones:

-Se realizán 3 visualizaciones que nos ayuden a comprender mejor los datos de la base.
-Primer gráfico: Muestra las ventas totales por tipo de producto y cantidad de grasa.
-Segundo gráfico: Muestra el promedio de ventas según el año de establecimiento del centro comercial.
-Tercer gráfico: Muestra un gráfico de pie que divide las ventas totales (porcentajes) según la localización de los centros comerciales.

Predicción de Ventas:

-Para realizar la predicción de nuestro target primero dropeamos las columnas que no aportan valor al modelo, luego estandarizamos la base, realizamos una correlación de valores (también con gráfico) y finalmente dividimos nuestra base en Train y Test.

Regresión Lineal:

-Primero creamos un modelo de regresión lineal, el cual nos da un valor del 50% en el Test.

KNN Regresión:

-Luego creamos un modelo de regresión KNN, el cual nos da un valor del 57% en el Test.

Random Forest Regressor:

-Finalmente, creamos un modelo de regresión Random Forest, el cual nos da un valor del 53% en el Test.

Conclusiones:

-El modelo de trabajo más óptimo para nuestra predicción seria el KNN, sin embargo, en la vida real, ningún modelo sería de utilidad, dado que ninguno supera siquiera el 60% de efectividad.
