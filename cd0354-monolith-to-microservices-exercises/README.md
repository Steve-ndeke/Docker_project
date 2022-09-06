# Monolith to Microservices Exercise and Demo Code

This repo contains code for all of the exercises in the Monolith to Microservices at Scale

## Lesson 1: Introduction to Microservices

No exercise or demos code

## Lesson 2: Microservices Design Principles and Best Practices

No exercise or demos code

## Lesson 3: Containers Using Docker

### Exercise Code

- [Create a Docker App](lesson-3-containers/exercises/docker-app-exercise/README.md)
- [Debugging](lesson-3-containers/exercises/debugging-exercise/README.md)
- [Base Images](lesson-3-containers/exercises/base-images-exercise/README.md)


### Build, Run, and Stop the Docker Image
1.Build the Docker image. The -t command allows us to give the container a name.
docker build -t simple_node .

2.Confirm that the image has been built

docker images

3.Copy the IMAGE ID and use it to run the Docker image

docker run {IMAGE ID}

4.pen a new terminal and print all of the running containers

docker ps

5.Copy the CONTAINER ID and use it to kill the Docker container

docker kill {CONTAINER ID}