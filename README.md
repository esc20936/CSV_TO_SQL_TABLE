# CSV_TO_SQL_TABLE
## Descripción
Este programa en Python esta hecho para convertir archivos **.CSV** a una tabla **SQL** en una base de datos.
El programa debe estar en la misma carpeta donde se encuentran los archivos **.CSV** .

## Requisitos
Se deben instalar los siguientes módulos
- pandas
- os
- glob
- sqlalchemy

Estos módulos se pueden instalar con el comando
```
pip install pandas os glob sqlalchemy
```
## Configuración
En el archivo de python encontraremos una sección para modificar los datos que necesitamos para la conexión
```
    user = "postgres" 
    password = "admin" 
    host = "localhost" 
    port = "5432" 
    database = "proyecto1" 
```

Donde **user** es el nombre de usuario de nuestro administrador de bases de datos, **password** es la contraseña, **host** por default es localhost(*127.0.0.1*), **port** es el puerto y **database** es el nombre de la base de datos donde queremos guardar las tablas **SQL** generadas.
