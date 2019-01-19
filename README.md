git@github.com:leon-do/nodejs-docker.git

cd nodejs-docker

docker build -t taghere ./

docker run -p 8081:8081 taghere

localhost:8081
