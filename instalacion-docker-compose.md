# INSTALACION DOCKER-COMPOSE CENTOS

Para su instalación, también procederemos a seguir los pasos de la [página oficial](https://docs.docker.com/compose/install/)

- Instalamos curl si no lo tenemos instalado
      
      sudo yum install curl
      
- Nos descargamos la version mas estable de docker-compose

      sudo curl -L "https://github.com/docker/compose/releases/download/1.27.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
      
- Le otorgamos permisos de ejecucion

      sudo chmod +x /usr/local/bin/docker-compose
      
