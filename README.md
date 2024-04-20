# Docker File Command:-
1. welcome-app is name of docker image
```
docker build -t {imagename} .
docker build -t {username/imagename} .
```
2. Check images of docker
```
docker images
```
3. Run Docker image
  hostport=5000 ,containerport=5000
```
docker run -p {hostport}:{containerport} welcome-app
docker run -d -p {hostport}:{containerport} welcome-app
```
4. List of running container
```
docker ps
```
5. Stop Docker Container
```
docker stop {container_id}
```
6. Login to Docker Hub
```
docker login
docker login -u my@email.com -p <REDACTED> 
```
7. Rename docker image
```
docker tag {imagename} {new_username}
```
8. Remove docker image
```
docker image rm -f {imagename}
```
9. Push Docker Image
```
docker push {image_name}:latest
```