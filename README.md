#Taller 1 Objetivo: Contar con las herramientas para iniciar el proceso de creación, subir y correr imágenes de docker.

1) Configuración de herramienta de desarrollo
2) Crear cuenta en Github: se crea la cuenta en github https://github.com/
3) Crear cuenta en Dockerhub: se crea la cuenta en dockerhub en https://hub.docker.com/ como se evidencia en la siguiente imagen se encuentra el ambiente de dockerhub con dos repositorios.
<p align="center">
<img src="https://github.com/NorelyJ/Administracion/blob/4b087b96c4fda1c05d7f4599e35e6803c45ec7a3/Docker_images/dockerhub.PNG">
</p>
4) Creación de repositorio: se crea le repositorio proyectoFinal_IAC en linux mediante la aplicacion MobaXterm_Portable_v23.0, se realiza el clon mediante el comando git clone https://github.com/NorelyJ/proyectoFinal_IAC.git como se puede visualizar en la siguiente imagen ya se encuentra el repositorio proyectoFinal creado. 
<p align="center">
<img src="https://github.com/NorelyJ/Administracion/blob/4b087b96c4fda1c05d7f4599e35e6803c45ec7a3/Docker_images/repositorio.PNG">
</p>
5) Configuración de llaves SSH: se configura las llaves en la consola de linux con el comando ssh-keygen y se copia la llave en github en la seccion SSH and GPG keys.

#Taller 2 Objetivo: Automatizar instalación de docker y Docker-compose

1) Agregar modulo de instalación de Docker en menú de administración para instalación y pruebas unitarias: se agrega el modulo de docker a la shell del taller 2 de sistemas operativos como se puede ver en la siguiente imagen.
<p align="center">
<img src="https://github.com/NorelyJ/Administracion/blob/4b087b96c4fda1c05d7f4599e35e6803c45ec7a3/Docker_images/Instal_docker.PNG">
</p>
2) Subir cambios a repositorio:Para subir cambios al repositorio se utiliza el comando git pull directamente en la consola de linux.

3) Clonar repositorio: se usa el link del repositorio a clonar del https que se encuentra en Code en github, como se puede ver en la siguiente figura en la parte derecha se encuentra de color verde con el comando git clone https://github.com/NorelyJ/proyectoFinal_IAC.git en la consola de linux.  
<p align="center">
<img src="https://github.com/NorelyJ/Administracion/blob/4b087b96c4fda1c05d7f4599e35e6803c45ec7a3/Docker_images/github.PNG">
</p>
5) Pruebas (docker –versión y Docker-compose --version): como se evidencia en la siguiente imagen se realizo la prueba del docker-compose en linux mediante el el archivo docker.compose.yml ya que se encuentra las images redis y app-py-web 
<p align="center">
<img src="https://github.com/NorelyJ/Administracion/blob/4b087b96c4fda1c05d7f4599e35e6803c45ec7a3/Docker_images/docker_install.PNG">
</p>




