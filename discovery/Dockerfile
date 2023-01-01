FROM eclipse-temurin:17.0.5_8-jre-alpine
RUN mkdir -p /home/app/
ADD target/discovery.jar /home/app/discovery.jar
CMD ["java","-jar","/home/app/discovery.jar"]