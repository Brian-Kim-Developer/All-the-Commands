# Docker

<br/><br/>
## Commands | () : type, [] : optional
### 1. Check existing docker version
```docker --version```
### 2. Get an image from docker engine
```docker pull (ex: ubuntu)```

### 3. See current images
```docker images```

### 4. Create a docker container from an image
```docker run -it -d (ex: ubuntu)```

### 5. See running docker containers
```docker ps```

### 6. See all docker containers
```docker ps -a```

### 7. Execute a docker container
```docker exec -it (container_id) bash```

### 8. Exit the docker container environment
```exit```

### 9. Stop running docker container
```docker stop (container_id)```

### 10. Remove stopped docker container
```docker [container] rm (container_id)```

### 11. Remove a docker image
```docker rmi (image_id)```

### 12. Stop and Remove all the docker containers at at time
```docker rm -f $(docker ps -a -q)```

### 13. Rename a docker image
```docker tag (old_image) (new_image)```
```docker rmi (old_image)```

### 14. Rename a docker container
```docker rename (old_container) (new_container)```

### 15. Login docker
```docker login```

### 16. Push a docker image to docker hub - repository
```docker tag (original_image) (repository_name):(tagname)```
```docker push (repository_name):(tagname)```


<br/><br/>
## References
### Docker Tutorial | Docker Tutorial for Beginners | What is Docker | Intellipaat
#### https://youtu.be/RppfZGuLsmA
