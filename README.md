# entorno_desarrollo_docker_nginx_php
Creamos un entorno de desarrollo con php 8.3 y carpeta compartida donde colocamos el proyecto a desarrollar.

Tener instalado docker para que pueda inciar la descarga de la imagen en docker.


Descargar el proyecto,  entrar dentro de la carpeta del proyecto e inicar la descarga
de la imágen en docker con el siguiente commando.

docker compose up -d

Una vez finalizado la descarga tendremos dos imagenes en docker,
para poder verlos listamos las imagenes en ejecusion.

docker ps

Las imagenes deberan tener los siguientes nombres

nginx_dev
php_dev

podremos visualizar el proyecto de archivo index.php en el puerto 8080.

http://localhost:8080/

Todos los cambios de edicion se realizan dentro de la carpeta 

entorno_desarrollo_docker_nginx_php/src/index.php










