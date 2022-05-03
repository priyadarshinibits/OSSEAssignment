FROM adoptopenjdk/openjdk11:ubi
RUN mkdir /opt/app
COPY target/*.jar /opt/app/rabbitasyncpublisher.jar
CMD ["java", "-jar", "/opt/app/rabbitasyncpublisher.jar"]
# docker run -d -p 6000:6000 --net=report-net --name rabbitasyncpublisher rabbitasyncpublisher:latest
