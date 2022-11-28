#docker login
docker build -t servicio-productos . -f .\Dockerfile
docker images
docker tag servicio-productos georgegxx/servicio-productos
docker push georgegxx/servicio-productos