# springboot-docker

The objective of this project is to utilize Docker to containerize a Spring Boot application. The process involves generating a Docker image for the application and subsequently deploying it within a Docker container.

 ## Disclaimer
1. This code is not original and was developed by following instructions from the YOUTUBE tutorial
"Dockerizing Spring Boot Application | Spring Boot Docker Tutorial | Docker Image" by Ramesh Fadatare.
2. In some cases, modifications or adaptations have been made to the original code to fit specific requirements or enhance functionality.
3. To access the original course materials and learn more, please refer to the
 "Dockerizing Spring Boot Application | Spring Boot Docker Tutorial | Docker Image" available here
(https://www.youtube.com/watch?v=RVIbMuNs1aw&t=1s&ab_channel=JavaGuides)

## Project Structure

1. Start by creating a Spring Boot application using the Spring Initializer.
2. Next, build a simple REST API by executing the command "mvn package" to maven build the project.
3. Proceed to create a Dockerfile. Navigate to the project's root directory, create a file named Dockerfile, and include the appropriate instructions such as "FROM", "LABEL", "ADD", and "ENTRYPOINT".
4. Build the Docker Image using the command "docker build -t springboot-docker:latest".
5. The fifth step involves running the Docker image in a container. Use the following command: "docker run -p 8081:8080 springboot-docker".
6. Finally, open a web browser and access the link "http://localhost:8081/hello" to view the response message of the REST API: "Spring Boot Docker".
