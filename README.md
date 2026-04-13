Foosball Application – Docker and GitHub Actions
Project Overview

This project demonstrates how to use Docker and GitHub Actions to automate building and deploying a containerized application. The Foosball application is packaged into a Docker image and automatically pushed to Docker Hub using a GitHub Actions workflow whenever code is pushed to the repository.

This setup helps simplify deployment and ensures the application can run consistently on different systems.

Use of Docker

Docker is used in this project to package the application into a container. A Docker container includes the application and all the dependencies it needs to run. This makes it easier to deploy and run the application on any machine without worrying about configuration differences.

In this project, Docker is used to:

Build a container image of the application
Store the image on Docker Hub
Run the application locally using a container
Use of GitHub Actions

GitHub Actions is used to automate the process of building and pushing the Docker image. When changes are pushed to the GitHub repository, a workflow automatically runs.

The workflow performs the following steps:

Checks out the code from the repository
Logs into Docker Hub using stored credentials
Builds the Docker image
Pushes the image to Docker Hub

This automation removes the need to manually build and upload Docker images.
