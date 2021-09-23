FROM adoptopenjdk:8u292-b10-jdk-hotspot-focal
COPY target/netty-http-echo-service-*.jar netty-http-echo-service.jar
ENTRYPOINT ["java", "-jar", "netty-http-echo-service.jar"]
