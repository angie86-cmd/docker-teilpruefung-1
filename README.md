# Docker Teilprüfung 1

## Build

docker build -t nginx-hallowelt:1.0 .

## Run

docker run -d --name nginx-hallowelt -p 8080:80 nginx-hallowelt:1.0

## Docker Hub

docker pull angie86cmd/nginx-hallowelt:1.0