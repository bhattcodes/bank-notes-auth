# Bank Note Authenticator
Docker Hub link : https://hub.docker.com/repository/docker/abxwolf/dockerhub/general </br>
data set link: https://www.kaggle.com/ritesaluja/bank-note-authentication-uci-data

<p align="center">
  <img width="auto" height="auto" src="/images/docker-1.jpg">
</p>

<p align="center">
  <img width="auto" height="auto" src="/images/docker-2.jpg">
</p>

## Steps to run this on your machine

- Download docker desktop on machine </br>
- Fork this repo then Pull the repo </br>
- `cd ..` to the pulled repo
- Execute this code to build an image 
  `docker build --tag python-docker .`</br>
- Execute this to run the above created image as a container
   `docker run --publish 5000:5000 python-docker` </br>
- visit `http://localhost:5000/apidocs` on your browser. to see the website
