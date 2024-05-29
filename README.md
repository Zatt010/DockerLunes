# DockerLunes
Docker donde Greeting se conecta con User y User con Identity 
git clone el repositorio
cd a example docker
crear imagenes:
         - los nombres estan en docker-compose.yaml: 
                 *greeting:latest
                 *client:latest
                 *identity:latest
         -Build para armar las imagenes con lo siguiente:
                 *docker build -t greeting:latest .
                 *docker build -t client:latest .
                 *docker build -t identity:latest .
(tambien construi cada imagen dentro de client y dentro de identity)
Ya creadas las imagenes hacer correr estas con docker
         -docker compose up
         - el comando se corre dentro de example-docker

En docker desktop deberia salir que ya estan todas arriba y corriendo
abrir localhost:9090/{id}
