FROM frolvlad/alpine-oraclejdk8:slim
#VOLUME /tmp
ADD ./target/demo-0.0.1.jar app.jar
#RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-jar","/app.jar"]
