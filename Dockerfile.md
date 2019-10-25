# Dockerfile

<br/><br/>
## Commands | () : type, [] : optional

### 1. FROM
#### selects an image on which you want to make changes
#### creates a layer from a docker image.
#### is always used at the first line of a docker file
```FROM (image)```

### 2. ADD
#### adds all files from a directory to inside of a docker container
```ADD . /var/www/html```

### 3. COPY
#### adds all files from a directory to inside of a docker container
```COPY . /app```

### 2. RUN
#### executes command(s) in a new layer and creates a new image
#### is often used for installing software packages
```RUN apt-get update```
```RUN apt-get -y install apache2```

### 2. CMD
#### sets default command and/or parameters, which can be overwritten from command line when docker container runs

### 2. ENTRYPOINT
#### configures a container that will run as an executable

### 2. ENV
#### 

<br/><br/>
## The bottem line
##### Use RUN instructions to build your image by adding layers on top of initial image.
##### Prefer ENTRYPOINT to CMD when building executable Docker image and you need a command always to be executed. Additionally use CMD if you need to provide extra default arguments that could be overwritten from command line when docker container runs.
##### Choose CMD if you need to provide a default command and/or arguments that can be overwritten from command line when docker container runs.
##### COPY only supports the basic copying of local files into the container, while ADD has some features (like local-only tar extraction and remote URL support) that are not immediately obvious. Consequently, the best use for ADD is local tar file auto-extraction into the image, as in ADD rootfs.tar.xz /.

<br/><br/>
## References

### Docker Documentation
#### https://docs.docker.com

### Docker Tutorial | Docker Tutorial for Beginners | What is Docker | Intellipaat
#### https://youtu.be/RppfZGuLsmA

### Docker RUN vs CMD vs ENTRYPOINT
#### https://goinbigdata.com/docker-run-vs-cmd-vs-entrypoint/
