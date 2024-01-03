# Introduction
Spring Boot Microservice - Simple Service Example

# Software needed
1.	Apache Maven (http://maven.apache.org). 
2.	Docker (http://docker.com). 
3.	Git Client (http://git-scm.com). 

# Building the Docker Images 
To build docker image, open a command-line window change to the directory, and run the following maven command.  This command will execute the [Spotify docker plugin](https://github.com/spotify/docker-maven-plugin) defined in the pom.xml file.  

   **mvn clean package docker:build**

If everything builds successfully you should see a message indicating that the build was successful.

# Running the Application

To start the docker image, Issue the following docker-compose command:

   **docker-compose -f docker/common/docker-compose.yml up**

