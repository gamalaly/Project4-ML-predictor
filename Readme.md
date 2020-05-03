[![CircleCI](https://circleci.com/gh/karimfadl/Operationalize-a-Machine-Learning-Microservice-API.svg?style=svg)](https://circleci.com/gh/karimfadl/Operationalize-a-Machine-Learning-Microservice-API)
# Operationalize-a-Machine-Learning-Microservice-API
Microservice Project [Udacity Cloud DevOps Engineer Nanodegree]

## Project Overview
Deploy a containerized Python flask application to serve out predictions (inference) about housing prices through API calls. It uses a a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features. 

### Project Procedure
* Test project code using linting
* Complete a Dockerfile to containerize this application
* Deploy containerized application using Docker and make a prediction
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate the code has been tested



---
## Getting Started
### Setup the Environment

* Create a virtualenv and activate it
```
python3 -m venv <your_venv>
source <your_venv>/bin/activate
```
* Run `make install` to install the necessary dependencies

### Running `app.py` Project

1. Deploy in Docker:  `./run_docker.sh`
2. Making predictions:  `./make_prediction.sh`
3. Upload the Docker Image:  `./upload_docker.sh`
4. Deploy in Kubernetes:  `./run_kubernetes.sh`
5. Making predictions again but via K8s:  `./make_prediction.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
