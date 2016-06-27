#Docker

###基本命令

docker —version
docker-compose —version
docker-machine —version

docker run -d  -p 80:80 —name webserver nginx

docker ps

docker inspect *containnername*

docker images

docker login —username=*yourusername* —email=*youremail@company.com*  登陆dockerhub

docker run  *yourusername/your-image-name*  运行镜像，如果不存在会自动下载

docker rm -f *containerid*

docker rmi -f *imageid*

###参考

1. [官方教程](https://docs.docker.com/engine/getstarted/)
2. [daocloud教程](https://dashboard.daocloud.io/nodes/new)
