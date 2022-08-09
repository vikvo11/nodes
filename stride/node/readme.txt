sudo apt update

docker-compose ps
docker-compose rm

docker stop $(docker ps -aq)
docker rm $(docker ps -aq)

docker image rm $(docker images -aq)

docker images
docker image ls
docker image rm


#commit
https://www.tecmint.com/install-run-and-delete-applications-inside-docker-containers/

 docker run -it ubuntu bash
 apt install nginx
 exit

docker ps -l
docker commit 5976e4ae287c ubuntu-nginx
docker images

Ctrl-p + Ctrl-q

# docker run -it ubuntu bash
# apt-get install nginx


# docker ps
# docker attach 3378689f2069
# exit