Simple spring boot application for docker and kubernetes exercise 

application url : localhost:8080/hello

Docker Commands
-------------------
Create docker file : `docker build -t spring-boot-demo-app-for-azure:1.0.0 .`

Get list of docker files : `docker images`

Run docker file in local (in interactive mode) : `docker run -it --rm -p 8080:8080 spring-boot-demo-app-for-azure:1.0.0`

Stop local container \
get container id from command : `docker ps` \
stop container by id : `docker stop <container_id>`