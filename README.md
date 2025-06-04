# Apache Docker App

This Dockerized Apache web server is designed for hosting static websites with ease and scalability.

## How to Use

### Build the image
#### Run the container
##### Push the image on Docker Hub
###### Pull from Docker Hub
```bash
docker build -t lalaaicha422/my-apache-app:v2 .
docker run -d -p 80:80 --name apache-container lalaaicha422/my-apache-app:v2
docker push lalaaicha422/my-apache-app:v2
docker pull lalaaicha422/my-apache-app:v2

