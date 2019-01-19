cd nodejs-docker

docker build -t taghere ./

docker run -p 8081:8081 taghere