Simplest python project to deploy to docker image

Useful commands:

 docker build -t hello-world-py .
 docker images
 docker run hello-world-py
 docker ps -a
 docker rm $(docker ps -a -q)