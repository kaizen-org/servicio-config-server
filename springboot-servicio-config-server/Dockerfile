FROM openjdk:11
VOLUME /tmp
EXPOSE 8888
ADD ./target/springboot-servicio-config-server-0.0.1-SNAPSHOT.jar config-server.jar
ENV USER=gabicasas
ENV PASS=TBD
ENV CONFIG_REPO=https://github.com/gabicasas/props-generic-crawler.git
ENV CODE_REPO=https://github.com/kaizen-org/crawler_test.git
ENTRYPOINT ["java", "-jar", "config-server.jar"]
#ENTRYPOINT ["java", "-jar", "config-server.jar", "-Dspring.cloud.config.server.git.uri=https://github.com/gabicasas/props-generic-crawler.git" , "-Dspring.cloud.config.label=main"]
#crear docker build config-server:v1 .
#

#docker run -p 8888<el que sea>:8888 --name <asdfafconfig-server> --network network-spring config-server:v1


