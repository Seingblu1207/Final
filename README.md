# INSTRUCCIONES UBUNTU:
1. Instalar Git en la maquina:
    - "sudo apt update"
    - "sudo apt install git"


2. Clonamos este repositorio en la ubicacion deseada:
    - "git clone https://github.com/Seingblu1207/Final"


3. Ingresamos a la carpeta que se crea al clonar el repositorio (En este caso es /Final) y ejecutamos el comando para construir el archivo docker:
    - "sudo docker build -t servermap:v01 ."


3. Finalizamos ejecutando el docker:
    - "sudo docker run -d -p 80:80 servermap:v01"


Y con esto ya esta listo, podemos comprobar el funcionamiento poniendo la IP publica del equipo en cualquier navegador
