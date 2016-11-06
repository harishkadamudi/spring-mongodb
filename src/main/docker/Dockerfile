FROM java:8
MAINTAINER harish.kadamudi@gmail.com
VOLUME /tmp
ADD gs-eizzy-userservice-0.1.0.jar app.jar
RUN sh -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]