# sample-docker-compose
This is a simple demonstration of how docker compose work


docker-compose is used to define multiple containers and define the network/connections between them.


https://docs.docker.com/compose/reference/overview/

Note docker-compose does not automatically come with the installation of docker. So, you would first download the docker compose file

Check if docker-compose is installed by running the command: `docker-compose --version`


Compose file version 3 reference and Guidelines:  https://docs.docker.com/compose/compose-file/


**Steps to create docker-compose and run the containers**

1. Create a folder named `docker`
2. Change to the newly created `docker` folder
3. Write the YAML file namely `docker-compose.yml` in the `docker` directory
4. While in the `docker` directory, build the `docker-compose.yml` file
5. To build this docker-compose file, the command is `docker-compose up -d`
6. Check to ensure all your containers are running
7. To stop and remove all the containers that have been launched from the docker-compose file, run the command `docker-compose down`. Note that you should still remain in the `docker` directory when you run this command
