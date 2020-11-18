FROM openjdk:11
VOLUME /tmp
EXPOSE 8888
ADD ./target/springboot-servicio-config-server-0.0.1-SNAPSHOT.jar config-server.jar
ENTRYPOINT ["java", "-jar", "config-server.jar"]
#crear docker build config-server:v1 .
#

#docker run -p 8888<el que sea>:8888 --name <asdfafconfig-server> --network network-spring config-server:v1


