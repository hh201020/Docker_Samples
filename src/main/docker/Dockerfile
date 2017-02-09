FROM openjdk:8-jre
VOLUME /tmp
ADD gs-spring-boot-docker-0.1.0.jar app.jar
RUN sh -c 'touch /app.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "/bin/bash" ]
