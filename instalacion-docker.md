# INSTALACIÓN DOCKER CENTOS

Para la instalación vamos a seguir los pasos de la [página oficial de docker](https://docs.docker.com/engine/install/centos/) aunque os pondre los pasos necesarios aqui.

- Vamos a configurar los repositorios

      sudo yum install -y yum-utils
      
      sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
      
- Procedemos a instalar docker engine (el motor de docker)

      sudo yum install docker-ce docker-ce-cli containerd.io
      
- Activamos el servicio de docker

      sudo systemctl start docker

