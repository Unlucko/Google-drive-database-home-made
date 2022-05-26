# Google-drive-database-home-made

El almacenamiento de los archivos se ha convertido en una parte importante de la vida humana, debido a que esto nos permite tener un orden de los archivos, poderlos compartir, tener un espacio propio y privado para ellos, poderlos ordenar, entre otras. Similarmente, es este proyecto de una base de datos que almacena los archivos, Google Drive database home made, es propuesto, diseñado y implementado. En este reporte se mostrara el proceso de creación y implementación serán explicados. Después de la explicación del proyecto, se mostrara los requerimientos y el diseño conceptual. 


Para que en PgAdmin4 se pueda visualizar los tablas, es necesario crear una base de datos llamada "Google Drive" luego se tiene que correr las creaciones, luego las inserciones y por ultimo las selecciones. 

En la parte de las creaciones, es necesario correr primero las tablas simples como lo son Archivo, Carpeta, Rol y Permisos, las cuales no dependen de ninguna otra tabla, luego es necesario correr las tablas dependientes, que como el nombre lo indica, dependen de estas tablas simples y por ultimo correr las tablas intermedias, para lograr exitosamente las creaciones, a la hora de insertar datos, bien se puede hacer manualmente, corriendo cada cosa en Pgadmin o si bien importando un archivo CSV con su respectivo codigo y ruta, ademas, de que estos archivos tienen que estar guardados en la carpeta de PgAdmin4 de su computador para lograr la importacion. Asi este dara paso a que se puedan hacer las selecciones y consultas de la base de datos. 

En python es necesario cambiar las partes de user y la contraseña por el usuario y contraseña de PgAdmin4.
