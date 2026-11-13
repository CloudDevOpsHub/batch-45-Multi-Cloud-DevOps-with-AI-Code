

 docker -v
    2  ls
    3  curl -fsSL https://get.docker.com -o install-docker.sh
    4  ls
    5  sudo sh install-docker.sh
    6  docker -v
    7  docker help
    8  docker pull nginx
    9  docker images
   10  docker rmi 165ddde8751e
   11  docker images
   12  docker run  nginx
   13  time docker run --rm hello-world
   14  for i in {1..34}; do docker run -d --rm alpine sleep 1000; done
   15  docker ps
   16  docker images
   17  docker stats
   18  docker run -it -d -p 8080:8080 jenkins/jenkins:latest
   19  docker ps
   20  docker ps | grep jenkins
   21  cat /var/jenkins_home/secrets/initialAdminPassword
   22  sudo cat /var/jenkins_home/secrets/initialAdminPassword
   23  cd /var/
   24  docker exec -it 119a1a31abed /bin/bash
   25  cd ~
   26  ls
   27  vi Dockerfile
   28  cat Dockerfile 
   29  docker images
   30  docker build -t anujimage .
   31  docker images
   32  docker tag af7db0adc4dc vikas4cloud/anujimage:latest
   33  docker images
   34  docker login
   35  docker push vikas4cloud/anujimage:latest
   36  history



FROM ubuntu
MAINTAINER clouddevopshub@gmail.com
RUN apt-get update
RUN apt-get install nginx -y
CMD [“echo”,”Image created”]
