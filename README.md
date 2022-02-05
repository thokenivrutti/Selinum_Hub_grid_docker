# Selinum_Hub_grid_docker
Selenium Hub / Grid on Docker Compose

**Question

Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration. In the lecture, we saw the example of docker-compose file for the mysql cluster Selenium is used by Software Testers (QA's) for testing the application on browser or via APIs. In this assignment, you need to write a docker-compose.yaml file to create a selenium cluster which is also called as Selenium Grid or Hub.

**Answer

Steps

Open terminal and Start our docker environment.

Create a docker-compose file as "docker-compose.yml" .

Then run a simple command as given :

docker-compose up -d

docker ps

Above command will create a selenium hub with a chrome node.
