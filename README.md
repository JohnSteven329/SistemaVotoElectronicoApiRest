# API RESTful  (Voto Electrónico 1.0.0)
Para iniciar Nuestro proyecto tenemos que tener listo el archivo Apirestfull y despues decomprimirlo y abrir eclipse y tener encuenta tener instalado el 
IDE de eclipse web delevoper. Luego vamos abrir nuestro xamp y vamos a activar el apache y el mysql.

Despues vamos al my sql luego ejecutamos Sql, puede ser con Xammp o cualquier otro conector de sql

ahora entramos a la consola de sql en el caso de usar Xammp pueden entrar en el navegador poniedo localhost/phpmyadmin/

aqui debemos crear una base de datos con el nombre sistemavotacion o cualquier nombre que deseas 

Luego abrir el archivo descargado del proyecto en eclipse y darle click derecho sobre la clase pricipal que seria ApiRestFulApplication.java

Darle en RunAs y seleccionamos SpringBootApp

Luego vamos al localhost/phpmyadmin/ y podemos volver a la consola de la base de datos y verificar que la tabla se haya creado correctamente

Y por ultimo  vamos a hacer las comprobaciones con insomnia o con Postman y verificar si podemos hacer POST y GETS

Una vez hecha la comprobacion veremos que si se guardan en la base de datos

## Prerequisitos
- Java JDK 21
- Spring Boot 3.3.1
- MySql 8
