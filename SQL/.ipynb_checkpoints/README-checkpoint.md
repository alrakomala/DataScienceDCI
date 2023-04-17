*Spreadsheet/Dataset:* Tabla. Análisis de una sola vez, sencillo de acceder y manipular. Tamaños limitados. 

*Database:* Conjunto de tablas. Puede manejar cantidades masivas de datos. Combina facilmente diferentes datasets. Automatización de extracción de datos para usar más de una vez.


# Structured Query Language (lenguaje de consulta estructurada) 

Lenguaje diseñado para administrar y recuperar información de _sistemas de gestión de bases de datos relacionales_.

Su alcance incluye la inserción de datos, consultas, actualizaciones y borrado, creación y modificación de esquemas y el control de acceso a los datos. Una de sus principales características es el manejo del álgebra y el cálculo relacional para efectuar consultas.

Existen varios _sistemas de gestión de bases de datos relacionales_ (plataformas), los más usados son:

* MySQL (open source)
* PostgreSQL (open source)
* SQLite (open source)
* MariaDB (open source)
* Oracle Database
* Microsoft SQL Server

-----

## Características de una tabla (o relación)

- Registros (lineas, renglones, tuplas)
- Campos (columnas)
- Cardinalidad: Número de registros
- Grado: Número de campos
- Esquema: estructura (campo, tipo de dato, nulos, descripción)

## Extracción de información a través de SQL

> SELECT column_name FROM table;

> SELECT column_name1, column_name2 FROM table
> ORDER BY column_name2;


En la práctica, para acceder a bases de datos con decenas de miles, millones o más registros, tendremos que conectarnos a un servidor. 
Es necesario conocer la dirección del servidos (HOST), puerto, usuario, y contraseña. 

Para la clase vamos usar una base de datos local (previamente descargada). 

Intslar _PostgreSQL_ o _MySQL Workbench_.