FROM openjdk:11
VOLUME /tmp
EXPOSE 8761
ADD ./target/springboot-servicio-eureka-server-0.0.1-SNAPSHOT.jar eureka-server.jar
ENTRYPOINT ["java", "-jar", "eureka-server.jar"]
#crear docker build config-server:v1 .
#

#docker run -p 8888<el que sea>:8888 --name <asdfafconfig-server> --network network-spring config-server:v1


