# Instalación

Para instalar Docker Portainer tendremos que crear un contenedor con la imagen portainer para ello utilizaremos el siguiente comando:


root@PC208:~/docker# docker run -d -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data --name portainer portainer/portainer


Con el siguiente comando hemos creado un contenedor ejecutado en segundo plano con el nombre portainer cogiendo la imagen portainer/portainer saliendo a tarves del puerto 9000.

