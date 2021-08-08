# docker-fibonacci

A react/express application that calculates the fibonacci number at a certain value. Uses docker to containerize multiple services(postgres, redis, react).

- React
- Node
- Amazon Web Services
- Docker
- Postgres
- Redis
- NGINX
- Travis CI

## Features
- Calculating fibonacci numbers at a certain value
- Cacheing numbers inputted using Redis
- Storing calculation values using Postgres

## Purpose
This project taught me how use Kubernetes to orchestrate the Docker files created from the docker-fibonacci version of the project. I learned a lot about many technologies and how they interact. Some things I learned include:
- Basic docker commands
- Containering applications using Docker
- Continous Integration using Travis CI
- Creating dockerfiles for production and staging environments
- Using docker-compose for production and staging environments
- Passing secrets through Docker containers
- Sending secrets to Travis CI
- Continous deployment to AWS Elastic Beanstalk
- Versioning dockerfiles and uploading to DockerHub
- Setting up NGINX as a load balancer
- Using LetsEncrypt for https
- Configuring postgres

Dockerhub: https://hub.docker.com/u/jbdiop
