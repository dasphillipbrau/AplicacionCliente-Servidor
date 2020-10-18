# AplicacionCliente-Servidor
Un conjunto de Aplicaciones Cliente y Servidor para una tienda ficticia. Incluye Script de creación de base de datos SQL Server

***Debido a que la aplicación utiliza una base de datos SQL Server, ud deberá ejecutar el archivo "Script de Creacion de BD.sql" incluido en la Carpeta "Archivos para Crear la BD" en su computadora para crear la BD respectiva y luego modificar el App.config dentro de la solución Servidor en VisualStudio para incluir la cadena de conexión adecuada para su instancia de SQL Server. De lo contrario las funciones de BD no servirán.***
La aplicación debería detectar dinámicamente la nueva cadena una vez la agregue a App.config.

El archivo .rar incluye código en 2 soluciones separadas para una aplicación cliente y otra aplicación servidor.
Ambas aplicaciones pueden funcionar de manera independiente, pero la mayoría de funciones de la aplicación cliente dependen de que se esté ejecutando la aplicación servidor y el servidor como tal se encuentre encendido.

Este proyecto demuestra los principios de conexión mediante TCP, así como el encapsulamiento de datos y la segregación de privilegios. 

Adentro también se encontrará un pequeño manual de uso para la aplicación.
