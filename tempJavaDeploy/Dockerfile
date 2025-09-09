#set the required Base image for the container
FROM openjdk:17-jdk-alpine

#create a working directory for the Container 
WORKDIR /app

#copy the JAVA src code into the image 
COPY src/Main.java /app/Main.java

#compile the JAVA code 
RUN javac Main.java

#run the JAVA app when container starts
CMD ["java" , "Main"]

