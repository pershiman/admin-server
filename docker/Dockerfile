FROM anapsix/alpine-java
VOLUME /tmp
ADD spring-boot-admin-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8093
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-jar","/app.jar"]
