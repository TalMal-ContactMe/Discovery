FROM openjdk:17-jdk
RUN mkdir -p /home/app/
ADD target/discovery.jar /home/app/discovery.jar
CMD ["java","-jar","/home/app/discovery.jar"]