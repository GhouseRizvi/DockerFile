##### DOCKEr FILES

Docker file is a declerative way of creating own docker image,
one needs to follow thw the docker file syntax to create own images.

file name should be Dockerfile

#### how to build image from Dockerfile
docker build -t [docker-hub-ur]/[usename]/[imagename]:version . (dot denotes the current directory)
ex: docker build -t dokcer.io/ghouserizvi/from:v1 .

#### how to push images to docker hub
docker push [docker-hub-ur]/[usename]/[imagename]:version
ex: docker push dokcer.io/ghouserizvi/from:v1
if the requested access is denied login as below 
docker login
username:
password.
