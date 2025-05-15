Comandos de linux o windows



## Linux 


CAT:
sudo:
sudo apt update:
sudo apt upgrade:
path: Muestra la rtua donde se encuentra actualmente en el bash 
ls: lista de contenido del directorio lo que equivale en windows "dir"
ls -a:
ls -l: aparace los archivos que estan dentro de la carpeta
cd nombre_de_la_carpeta 
clear: para limpiar la pantalla 
mkdir: para crear carpetas 
man (ver la ayuda de los comando que se de, en este caso touch) touch: para crear archivos Ejemplo: touch papas.yml
yml: yaml Es un tipo de archivo que se usa conmumente 
tree: para ver el arbol de carpetas 

Comandos de docker 
docker ps para ver los contenedores que hay en ejecucion 
para encontrar paginas se va a docker hub y se busca las imagenes, luego se copea segun el procesador el tag 

docker stop nombre_dela_maquina
docker start "id o nombre"
$ docker run -it ubuntu bash: es para correr una imagen directamente desde el contenedor
$ docker ps -a mostrar contenedores prendidos y apagados
como nos conectamos a la terminal de un contenedor?
docker exec -it codigo del contenedor bash
docker run -d --name
docker container rm id contenedero es para borrar
docker images para ver la imagenes
docker rmi nombre de la imagen para borrar al imagen
docker search ubuntu: 
docker run -it: activar una consola y quedar dentro de ella 
docker pull <debian:unstable-slim>:unstable-slim 
  → Es la etiqueta (tag) que especifica la versión:
  unstable → es la rama de desarrollo más reciente (no recomendada para producción).
  slim → es una versión ligera (sin herramientas innecesarias, ideal para contenerizadores minimalistas)



  ---- docker file de back end y frontend 
  
