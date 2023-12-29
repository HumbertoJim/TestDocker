# TestDocker
 
En este repositorio se sigue el tutorial de [Guía de docker para principiantes, cómo crear tu primera aplicación docker](https://www.freecodecamp.org/espanol/news/guia-de-docker-para-principiantes-como-crear-tu-primera-aplicacion-docker/).

Pasos para ejecutar el código.
 1. Crear tu imagen
    * **docker build -t [the name that you wnat for your image] .**
 2. Muestra las imagenes creadas
    * **docker image ls**
 3. Crea tu contenedor, la instancia de tu imagen (pueden haber varios contenedores a partir de una misma imagen).
    * **docker run --name [the name that you want for your container] [your image name]**
 4. Muestra tus contenedores creados
    * **docker ps -a**
 5. Elimina tu contenedor
    * **docker rm [your container name]**
 6. Elimina tu imagen (no puedes eliminar una imagen si tienes contenedores que fueron instanciados de él)
    * **docker image rm [your image name]**