# Use the official OpenJDK base image
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the compiled Java application JAR file into the container
COPY HelloWorld.class /app/HelloWorld.class

# Run the Java application
CMD ["java", "HelloWorld"]
