# Videoclub
Base de datos de videoclub en PostgreSQL: modelado relacional, normalización y consultas de disponibilidad de copias.


En esta práctica se realizó el modelado y normalización de una base de datos para un sistema de videoclub utilizando PostgreSQL. A partir de una tabla temporal con datos desnormalizados (tmp_videoclub), se diseñó un modelo relacional compuesto por las entidades socio, dirección, película, copia y renta, definiendo sus relaciones mediante claves primarias y foráneas.

Posteriormente se cargaron los datos en las tablas normalizadas mediante consultas INSERT ... SELECT. Finalmente, se implementaron consultas  para identificar copias disponibles de las películas, utilizando LEFT JOIN y detección de ausencia de relación (IS NULL) para determinar qué copias no tienen rentas activas.

Este ejercicio demuestra el proceso de normalización de datos, creación de relaciones entre tablas y construcción de consultas para gestionar la disponibilidad de películas dentro del sistema.


# Estructura del script

El script SQL realiza las siguientes acciones:

1. Creación de tablas normalizadas.

2. Definición de claves primarias y foráneas.

3. Creación de la tabla temporal tmp_videoclub.

4. Inserción de datos desde la tabla temporal hacia las tablas normalizadas.

5. Consultas para determinar la disponibilidad de copias.



# Tecnologías utilizadas:

-PostgreSQL
-SQL
-DBeaver
-draw.io
