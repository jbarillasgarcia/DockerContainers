# Docker Containers

## Dockerfile
Basic Dockerfile contents should be as follows:

### Java 8
- FROM java:8
- COPY . /var/www/java
- WORKDIR /var/www/java
- RUN javac HelloWorld.java
- CMD ["java", "HelloWorld"]

### OpenJDK 8
- FROM openjdk:8
- COPY . /usr/src/myapps
- WORKDIR /usr/src/myapps
- RUN javac HelloWorld.java
- CMD ["java -jar", "HelloWorld"]
