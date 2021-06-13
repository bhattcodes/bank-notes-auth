# docker ML

data set link: https://www.kaggle.com/ritesaluja/bank-note-authentication-uci-data

<p align="center">
  <img width="auto" height="auto" src="/images/docker-1.jpg">
</p>

<p align="center">
  <img width="auto" height="auto" src="/images/docker-2.jpg">
</p>

## Steps to run this on your machine

Download docker desktop on machine </br>
pull this repo </br>
`docker build --tag python-docker .` , execute this code to build an image </br>
`docker run --publish 5000:5000 python-docker` , execute this to run the above created image as a container </br>
visit `http://localhost:5000/apidocs` on your browser. to see the website
