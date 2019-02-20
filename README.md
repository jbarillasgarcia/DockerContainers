# DockerContainers

##Dockerfile
Basic Dockerfile contents should be as follows:

- FROM java:8
- COPY . /var/www/java
- WORKDIR /var/www/java
- RUN javac HelloWorld.java
- CMD ["java", "HelloWorld"]
