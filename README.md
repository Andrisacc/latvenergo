# Flask Sample App for Docker

This is a simple Python Flask application designed to be containerized with Docker.

## Getting Started

These instructions will cover usage information and for the docker container 

### Prerequisities

In order to run this container you'll need docker installed.

* [Windows](https://docs.docker.com/docker-for-windows/install/)
* [OS X](https://docs.docker.com/docker-for-mac/install/)
* [Linux](https://docs.docker.com/engine/install/)

### Building the Docker Image

docker build -t flask-sample-app .

### Container Parameters to run

Run the docker container with the following command:

docker run -d -p 4000:5000 flask-sample-app
