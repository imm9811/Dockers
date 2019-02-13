1.- Instalaremos Laravel , pero antes CLARAMENTE tendremos que tener INSTALADO nuestro docker
Nos bajamos la imagen del docker compose

sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

Nos instalar el docker compose

sudo apt install docker-compose


Instalar laravel con bitnami
primero creamos un directorio de prueba para ver que funciona bien

y pondremos LOS 3 SIGUIENTES COMANDOS:

sudo mkdir ~/myapp && cd ~/myapp
sudo curl -LO https://raw.githubusercontent.com/bitnami/bitnami-docker-laravel/master/docker-compose.yml
sudo docker-compose up

Primer nos crea la carpeta donde se alojaran los archivos que bajaremos de la imagen con la url del siguiente comando
Segundo nos bajamos la imagen
Tercero levantamos el servicio


--fuente original--
https://hub.docker.com/r/bitnami/laravel/
