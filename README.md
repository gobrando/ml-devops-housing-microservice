[![gobrando](https://circleci.com/<gh>/gobrando/ml-devops-housing-microservice.svg?style=svg)](https://app.circleci.com/pipelines/github/gobrando/ml_housing_microservice)
## Project Overview

We've built a machine learning model to predict housing prices in the Boston area now it's time to deploy the model into production using Docker and Kubernetes with linting using CircleCi

In this repo you'll file config files for a local build, Docker, Kubernetes, and CircleCI. Output files for the predictions that end in '_out' and shell scripts to deploy and run a prediction.

To run in Docker:  `./run_docker.sh`
To run in Kubernetes first enable K8 with either 'start minikube' or using Docker Desktop then run:  `./run_kubernetes.sh`
