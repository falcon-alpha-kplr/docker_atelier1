# docker_atelier1

gitpod /workspace/docker_atelier1 (main) $ docker --version  
Docker version 23.0.3, build 3e7cbfd
gitpod /workspace/docker_atelier1 (main) $ docker ps  
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES  
gitpod /workspace/docker_atelier1 (main) $ docker images    
REPOSITORY   TAG       IMAGE ID   CREATED   SIZE  
gitpod /workspace/docker_atelier1 (main) $ docker pull hello-world    
Using default tag: latest  
latest: Pulling from library/hello-world  
719385e32844: Pull complete   
Digest: sha256:a13ec89cdf897b3e551bd9f89d499db6ff3a7f44c5b9eb8bca40da20eb4ea1fa  
Status: Downloaded newer image for hello-world:latest  
docker.io/library/hello-world:latest  
gitpod /workspace/docker_atelier1 (main) $ docker images  
REPOSITORY    TAG       IMAGE ID       CREATED       SIZE  
hello-world   latest    9c7a54a9a43c   7 weeks ago   13.3kB  
gitpod /workspace/docker_atelier1 (main) $ docker run hello-world  

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/

gitpod /workspace/docker_atelier1 (main) $ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
gitpod /workspace/docker_atelier1 (main) $ docker run hello-world

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/

gitpod /workspace/docker_atelier1 (main) $ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
gitpod /workspace/docker_atelier1 (main) $ docker ps -a
CONTAINER ID   IMAGE         COMMAND    CREATED          STATUS                      PORTS     NAMES
862209ec88fe   hello-world   "/hello"   16 seconds ago   Exited (0) 15 seconds ago             naughty_chatelet
e415412f08ec   hello-world   "/hello"   8 minutes ago    Exited (0) 8 minutes ago              amazing_mirzakhani
gitpod /workspace/docker_atelier1 (main) $ docker rm e415412f08ec
e415412f08ec
gitpod /workspace/docker_atelier1 (main) $ docker rm 862209ec88fe
862209ec88fe
gitpod /workspace/docker_atelier1 (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
gitpod /workspace/docker_atelier1 (main) $ docker images
REPOSITORY    TAG       IMAGE ID       CREATED       SIZE
hello-world   latest    9c7a54a9a43c   7 weeks ago   13.3kB
gitpod /workspace/docker_atelier1 (main) $ docker image rm hello-world
Untagged: hello-world:latest
Untagged: hello-world@sha256:a13ec89cdf897b3e551bd9f89d499db6ff3a7f44c5b9eb8bca40da20eb4ea1fa
Deleted: sha256:9c7a54a9a43cca047013b82af109fe963fde787f63f9e016fdc3384500c2823d
Deleted: sha256:01bb4fce3eb1b56b05adf99504dafd31907a5aadac736e36b27595c8b92f07f1
gitpod /workspace/docker_atelier1 (main) $ docker images
REPOSITORY   TAG       IMAGE ID   CREATED   SIZE
gitpod /workspace/docker_atelier1 (main) $ 
