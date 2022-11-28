#docker login
docker build -t servicio-item . -f .\Dockerfile
docker images
docker tag servicio-item georgegxx/servicio-item
docker push georgegxx/servicio-item