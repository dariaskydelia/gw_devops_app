Dockerfile build image with app on port 8888:
docker build -t java_app .
docker run -d java_app

Dockerfile_norun build image and need to use:
docker build -t java_norun .
docker run -d java_norun java -jar spring-boot-sample-web-ui-2.2.6.RELEASE.jar --server.port=7777

check container status:
docker logs name_of_container
