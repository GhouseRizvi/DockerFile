## Volume 
docker containers are ephemerals it'll remove the container it'll delete the data as well
to save the data docker provide docker volume.
here volume data will remain intact even if the container is deleted
Docker store the volumes under 
/var/lib/docker/
Here we've overlay in this docker saves all the data and create random ID and store the information 

if you create volumes 
_________________________________
/var/lib/docker/volume/
here it is create docker volumes 

syntax
docker volume craete volume [name-of-volume]
docker volume ls
docker volume inspect nginx

 "Mountpoint": "/var/lib/docker/volumes/nginx/_data",

how to attach volumes to the container

docker run -d -v nginx:/usr/share/nginx/html -p 80:80 nginx

once container is created you can add or remove the content from the below location
cd /var/lib/docker/volumes/nginx/_data

___________________________________________
Docker annonymous volumes
mkdir test
docker run -d -v /home/ec2user/test/:/usr/share/nginx/html/ -p 80:80 nginx

it'll mount to a atest anonymous volume 
when you do docker volume ls
it should not be avaiable in your volume list because its not managed by docker.

in docker we've a volume instructions
