# ProyectoU2
# Empezamos con importar las librerias y todo lo que vamos a utilizar.
# Cargamos el dataset e imprimemos la informacion.
# Lo primero es hacer que se diferencien los tipos de datos y asi se identificaran los numericos y los tipo objeto.
# Se imprimen tanto la cantidad como las columnas numericas y tipo objeto.
# Se hace un conteo de nulos y se ordenan de forma descendente.
# Imprimimos los datos estadisticos de las variables.
# En este caso yo vi valido la categorizacion de country por continente, asi que imprimo los paises que estan sin repetir.
# Ya despues lo categorizamos todo junto por continente.
# Identificamos las columnas numericas con anomalias con graficos asi mismo tambien con las columnas tipo objeto, si tenian inconsistencias, lo hacemos por columna.
# Tambien mostramos las correlaciones de pearson y spearman
# volvemos a mostrar graficos.
# Ahora vamos a la manipulacion de los datos.
# este caso no hubo demasiados nulos en as columnas, asi que primero le ponemos el limite del 5%. luego vemos que columnas son las que lo exceden, que son dos uno que la sobre pasa para estos a uno lo hacemos con la moda, y el otro con la mediana.
# Mostramos las columnas que en las que se eliminaran nulos y los eliminamos.
# Convetimos columnas que se veian bien para convertir en tipo categoricas.
# Ahora generamos el df_numeric donde solo tendra las columnas numericas y mostramos las columnas con mayor dispersion y mostramos columnas con las dipersion para eso usamos un for.
# Contestamos las preguntas
# ¿Considera que con los datos numéricos actuales se pueden realizar predicciones para la columna "line_item_insurance_usd"?
# Si, con los datos numericos actuales es posible realizar predicciones para la columna line_item_insurance_usd, esta variable se puede predecir en funcion de las otras variables numericas en el conjunto de datos.

# ¿Considera que con los datos numéricos actuales se pueden realizar predicciones para la columna "late_delivery"?
# Sí, con los datos numéricos actuales es posible realizar predicciones para la columna late_delivery.
# Para realizar prediciones sobre esta variable, se puede utilizar un modelo de clasificacion.
# ¿Cree que alguna otra columna (objeto o categórica) se pueda correlacionar fuertemente con "late_delivery"?, si es así, ¿cuál o cuáles cree que tendrían una correlación fuerte?
# Es posble, pero se necesita verificar cual es la que tiene mayor relacion.
# En esta parte mostramos la correlacion del DataFrame numerica y el completo.
# construimos el modelo de regresion lineal.
# genramos la hipotesis, tanto la nula como la alternativa.
# sacamos la distribucion bootstrap.
# Calculamos z y hacemos las pruebas, que en la conclusion alternativa se comento.