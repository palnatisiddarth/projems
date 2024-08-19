# Use a base image with Java installed
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container
COPY /target/Eureka_EKA-0.0.1-SNAPSHOT.jar /app/eureka.jar

# Expose the port the application will run on (adjust if necessary)
EXPOSE 8080

# Command to run the application
ENTRYPOINT ["java", "-jar", "eureka.jar"]
