![gimmy1](https://circleci.com/gh/gimmy1/ml-api.svg?style=svg)

## Project Overview

Operationalize Machine Learning Microservice API.

You are given a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on the data source site. This project tests your ability to operationalize a Python flask app—in a provided file, app.py—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

## Technologies
- [Docker](https://www.docker.com/)
- [Kubernetes](https://kubernetes.io/releases/download/)
- [Python](https://www.python.org/)

## Run the application
1. `make all`
2. `./run_docker.sh` * Spins Docker container
3. `./run_kubernetes.sh` * Spins up Local Kubernetes Cluster
4. `python app.py` * Serves Local Server


## Mentions:
- The libraries are outdated and so it will not make predictions. If you choose to extend, you will have to sort
through the ML libraries and update wherever necessary. This is intended as a base model. :) Extend as you want.