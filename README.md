# ENTREGA N°2 SPRING - Taller de Base de Datos #

--------------------------------------
*Integrantes grupo 4:

-LOBOS BUSTOS FABIAN ANDRES
-CIFUENTES ZURITA JAVIER ALEJANDRO
-VÁSQUEZ FIGUEROA JORGE MANUEL
-SARMIENTO MERANI BÁRBARA FRANCISCA
-PIZARRO RIFFO ALBERTO ANDRÉS

---------------------------------------
*Requerimientos

1. Tener instalada la base de datos Sakila (instrucciones aquí: https://dev.mysql.com/doc/sakila/en/sakila-installation.html)
2. Modificar el archivo "tallerBackend/src/main/resources/application.properties" en las líneas número 3 y 4 para colocar vuestras credenciales
3. Tener instalado gradle
---------------------------------------
*Instrucciones de ejecución 

1. Ingresar a la carpeta del proyecto (tallerBackend)
2. Abrir la terminal dentro de la carpeta (click derecho->abrir terminal)
3. En la terminal ejecutar "gradle build" para compilar el proyecto
4. Una vez terminada la compilación ejecutar "gradle bootrun" para poner en funcionamiento el proyecto
---------------------------------------
*Instrucciones de uso

Se recomienda el uso del programa "Postman" para probar la ejecución de las siguientes instrucciones. 
Todas inician en la URL: http://localhost:8081/sakila-spring-backend/

GET

/actors/1/films --> retorna todas las películas en las que ha participado el actor 1.

/films/1/actors ---> retorna todos los actores de la película 1.

POST

/actors/1/films/2 --> vincula la película 2 al actor 1. (se debe validar que exista la película 2).

/films/1/actors/2 --> vincula el actor 2 a la película 1. (se debe validar que exista la actor 2).

Errores

En caso de recibir un aviso de error por parte del servidor se puede deber a:

1. URL errónea/mal escrita
2. ID del actor no encontrada 
3. ID de la película no encontrada
-----------------------------------------
