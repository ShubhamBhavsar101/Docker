# Docker Compose

## Docker
Docker as a platform manages the lifecycle of your container.

## To containerize
1. Create a dockerfile
2. Decide Base Image
3. Using Run Install all the dependencies in Docker image
4. Expose a port.
5. Using a entrypoint/cmd, execute a command when container is started.
6. Create docker image by building the dockerfile.

## To Run the image
1. Docker run command to run the container with port and name mentioned.

## If docker can manage the lifecycle of container, why to go for Docker Compose?
1. Docker compose is a tool developed by docker inc.
2. Docker compose is used to manage multi-container applications.
3. Without Docker compose
   a. need to run multiple docker run and docker build commands.
   b. Need to consider dependencies while launching containers/microservices.
4. If the developer wants to test his code, he doesn't need to deploy his code to kubernetes cluster to test on his local machine.
5. Yaml is a standard that is backwards compatible or mostly compatible.


