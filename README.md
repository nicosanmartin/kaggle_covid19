# COVID 19

### Consideraciones Diagrama:

<!> Day Wise no lo relacioné con ninguna otra tabla porque solo tiene registros a nivel fecha, y no a pais o estado como  las demás. En caso de que el analisis se realice por fecha, sin apertura, podría relacionarse.

<!> Relacioné tablas en casos donde una de ellas tiene aperturado por Pais y otra por Pais, State por si se realiza un agrupado.

### Consideraciones Desarrollo:

<!> Para cada uno de los esquemas definidos en los Dataframe's, no se hace validación de los datos, como por ejemplo, que una columna no contenga valores nulos (a través del párametro nullable), así como tampoco la adición de metadata.

<!> Si bien en la descripción del challenge se especifica que los datos deben ser tratados en la última capa, de todas formas se proporciona una manera por la cual los datasets pueden ser leidos especificando el esquema previamente.

<!> No se realiza manejo de excepciones.

<!> No se realiza limpieza de los nombres de las columnas.
