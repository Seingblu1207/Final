# INSTRUCCIONES UBUNTU:
1. Instalar Git en la maquina:
    - "sudo apt update"
    - "sudo apt install git"


2. Clonamos este repositorio en la ubicacion deseada:
    - "git clone https://github.com/Seingblu1207/Final"


3. Ingresamos a la carpeta que se crea al clonar el repositorio (En este caso es /Final)


4. Instalamos DockerFile para poder manipular los contenedores:
    - "sudo apt install docker.io"


5. Ejecutamos el comando para construir el archivo docker:
    - "sudo docker build -t servidor:v1.1 ."


6. Finalizamos ejecutando el docker:
    - "sudo docker run -d -p 80:80 servidor:v1.1"


Y con esto ya esta listo, podemos comprobar el funcionamiento poniendo la IP publica del equipo en cualquier navegador
