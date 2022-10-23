# Curso Docker

Curso sobre contenedores Docker.

## 1. Introducción a los contenedores Docker
* Introducción a Docker
* [Instalación de docker](modulo1/instalacion.md)
* [El "Hola Mundo" de docker](modulo1/holamundo.md)
* [Ejecución simple de contenedores](modulo1/contenedor.md)
* [Ejecutando un contenedor interactivo](modulo1/interactivo.md)
* [Creando un contenedor demonio](modulo1/demonio.md)
* [Creando un contenedor con un servidor web](modulo1/web.md)
* [Configuración de contenedores con variables de entorno](modulo1/configuracion.md)

## 2. Imágenes Docker 
* [Registros de imágenes: Docker Hub](modulo2/dockerhub.md)
* [Gestión de imágenes](modulo2/gestion.md)
* [¿Cómo se organizan las imágenes?](modulo2/organizacion.md)
* [Creación de contenedores desde imágenes](modulo2/creacion.md)
* [Ejemplo: Desplegando la aplicación mediawiki](modulo2/mediawiki.md)

## 3. Almacenamiento y redes en Docker 
* [Volúmenes docker y bind mount](modulo3/volumenes.md)
* [Asociando almacenamiento a los contenedores: volúmenes Docker](modulo3/asociacion_volumen.md)
* [Asociando almacenamiento a los contenedores: bind mount](modulo3/asociacion_bind_mount.md)
* [Redes en Docker](modulo3/redes.md)
* [Redes definidas por el usuario](modulo3/redes_usuario.md)
* [Ejemplo 1: Despliegue de la aplicación Guestbook](modulo3/guestbook.md)
* [Ejemplo 2: Despliegue de la aplicación Temperaturas](modulo3/temperaturas.md)
* [Ejemplo 3: Despliegue de Wordpress + mariadb](modulo3/wordpress.md)
* [Ejemplo 4: Despliegue de tomcat + nginx](modulo3/tomcat.md)

## 4. Creando escenarios multicontenedor con docker-compose 
* [Creando escenarios multicontenedor con docker-compose](modulo4/instalacion.md)
* [El fichero docker-compose.yml](modulo4/docker-compose.md)
* [El comando docker-compose](modulo4/comando.md)
* [Almacenamiento con docker-compose](modulo4/alamacenamiento.md)
* [Ejemplo 1: Despliegue de la aplicación Guestbook](modulo4/guestbook.md)
* [Ejemplo 2: Despliegue de la aplicación Temperaturas](modulo4/temperaturas.md)
* [Ejemplo 3: Despliegue de Wordpress + mariadb](modulo4/wordpress.md)
* [Ejemplo 4: Despliegue de tomcat + nginx](modulo4/tomcat.md)

## 5. Creación de imágenes en docker 
* Creación de imágenes a partir de un contenedor
* Creación de imágenes a partir de un Dockerfile
* Distribución de imágenes
* Ejemplo 1: Construcción de imágenes con una página estática
* Ejemplo 2: Construcción de imágenes con una una aplicación PHP
* Ejemplo 3: Construcción de imágenes con una una aplicación Python
* Ejemplo 4: Construcción de imágenes configurables con variables de entorno
* Ciclo de vida de las aplicaciones
