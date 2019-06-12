# Dockerized-SpringBoot-App
Sample Spring boot application that runs inside of a Docker container

# Instructions for running application inside of Docker Container
1. Download Docker 
2. Navigate to the directory where the spring boot application is located on your file system
3. Run command docker build -t spring-boot-docker.jar "." <-- add period at the end for the Root, press enter and let it build.
4. Once built successfully run command docker run -p 9090:8080 spring-boot-docker.jar
    > -p 9090:8080 is a port mapping that allows your localhost:9090 to map to port 8080 inside of the Docker Container
5. Go to Browser, type http://localhost:9090/message

Have fun expand upon the functionality! :)
