# Start with the base image containing Java-Runtime
FROM openjdk:17-jdk-slim

#Information who maintains the image
MAINTAINER Zahid

# Add the application's jar to the image
COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

# execute the application
ENTRYPOINT [ "java", "-jar", "accounts-0.0.1-SNAPSHOT.jar" ]