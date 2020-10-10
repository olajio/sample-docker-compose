# sample-docker-compose
This is a simple demonstration of how docker compose work


docker-compose is used to define multiple containers and define the network/connections between them.


https://docs.docker.com/compose/reference/overview/

Note docker-compose does not automatically come with the installation of docker. So, you would first download the docker compose file

Check if docker-compose is installed by running the command: `docker-compose --version`


Compose file version 3 reference and Guidelines:  https://docs.docker.com/compose/compose-file/


**Steps to create docker-compose and run the containers**

1. Create a folder named `docker`
2. Write the sample YAML file in "docker-compose.yml" file
3. To build this docker-compose file, the command is `docker-compose up -d`
4. Ensure all your containers are running
