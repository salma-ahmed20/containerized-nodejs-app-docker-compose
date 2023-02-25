# containerized-nodejs-app-docker-compose
This repo is about containerizing nodejs , redis and express Application and load balancing solution with 
docker compose and Nginx

## What is Docker Compose? 
Docker Compose is a tool that was developed to help define and 
share multi-container applications. With Compose, we can create a YAML file to define the services and with a single command,
can spin everything up or tear it all down.

## What is NGINX?
NGINX is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more. 

## Steps
- creating docker file for NGINX.
- creating two docker files for the two websites that will use NGINX load balancer on.
- creating docker compose yml file that will define the services we will use (redis, nginx, two websites)

