# DockerUbuntuNode
Imagen Ubuntu implementada con Node 16.13.1
Imagen para desarrollo de aplicaciones node previas a la dockerización.

Contiene:

Ubuntu 20.04

Node 16.13.1

git 2.25.1

nano

Ejecutar en la carpeta del archivo Dockerfile

- docker build .

Luego de la compilación de la imagen:

- docker image ls

- docker image tag xxxid_imagenxxx nombre:tag

- docker run -ti nombre:tag /bin/bash




