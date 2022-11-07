# SIAM_proxy
repositorio para dejar el proxy inverso de la app SIAM

Primero buildeamos la imagen

    docker build -t swarch2022ii_proxy .

Iniciamos el contenedor

    docker run -p 80:80 swarch2022ii_proxy
