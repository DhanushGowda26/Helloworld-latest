# Java Web App Dockerization with Jenkins CI/CD

This project demonstrates the automation of building and deploying a Java-based static web application using Jenkins CI/CD. The CI/CD pipeline builds a Docker image from a Dockerfile (with Tomcat as the base image), pushes it to Docker Hub, and runs the container.

## Prerequisites

Before setting up this CI/CD pipeline, ensure you have the following prerequisites:

- Jenkins server up and running.
- GitHub repository for your Java web application.
- Docker installed and configured on your build machine.
- Docker Hub account for storing the Docker images.

## Setup

1. **Configure Jenkins to integrate with your GitHub repository**.

2. **Set up Jenkins jobs for building and deploying the Docker image**.

3. **Configure Jenkins to trigger the build job on new commits**.

4. **Update the Dockerfile with your Java web application's configurations**.

5. **Update the Jenkinsfile to include the necessary Docker build and push steps**.

## Usage

1. Push changes to your GitHub repository.

2. Jenkins will automatically trigger the CI/CD pipeline.

3. Monitor the Jenkins build logs for any issues.

4. Access the deployed Docker container from Docker Hub.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make your changes and commit them.

4. Push your changes to your forked repository.

5. Create a pull request to merge your changes into the main repository.
