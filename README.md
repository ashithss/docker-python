# Version
```
python3 --version
Python 3.10.12

pip --version
pip 22.0.2 from /usr/lib/python3/dist-packages/pip (python 3.10)
```

# Steps to run application Manually
1. git clone https://github.com/ashithss/docker-python.git
2. cd docker-python
3. pip install --no-cache-dir -r requirements.txt
4. python3 app.py
5. Your application will run in 5000 Port:- http://localhost:5000/

# To test docker image

1. git clone https://github.com/ashithss/docker-python.git
2. cd docker-python
3. docker build -t flaskApp:latest .
4. docker run --name FlaskApp -it -p 5000:5000 -d flaskApp:latest
5. Your application will run in 5000 Port:- http://localhost:5000/


# Screenshots - GitHub Copilot

![Image Alt text](Images/image.png "Application")


# Python Flask Application

This repository contains a Python Flask application, along with a Dockerfile and a Jenkinsfile for building and deploying the application using Docker and Jenkins.

## Overview

- **Flask Application**: A Python Flask web application that provides a simple API or web interface.
- **Dockerfile**: A Docker configuration file used to build a Docker image for the Flask application.
- **Jenkinsfile**: A Jenkins pipeline script that automates the build, test, and deployment processes for the Flask application using Docker.

## Prerequisites

- Docker
- Jenkins
The Flask application should now be accessible at `http://localhost:5000`.

## Continuous Integration and Deployment

This project uses Jenkins for Continuous Integration and Deployment (CI/CD). The `Jenkinsfile` was generated by GitHub Copilot and defines the pipeline stages for building, testing, and deploying the Flask application using Docker.

1. Set up Jenkins and configure it to use this repository.
2. Create a new Jenkins pipeline job and point it to the `Jenkinsfile` in this repository.
3. Configure any necessary environment variables or credentials required by the pipeline.
4. Run the Jenkins job to trigger the CI/CD pipeline.




