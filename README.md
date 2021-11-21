![gimmy1](https://circleci.com/gh/gimmy1/ml-api.svg?style=svg)

## Project Overview

Operationalize Machine Learning Microservice API.

You are given a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing). This project tests your ability to operationalize a Python flask app—in a provided file, `app.py`—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.


## Environment Setup

-   Create a virtualenv and activate it
-   Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone: `python app.py`
2. Run in Docker: `./run_docker.sh`
3. Run in Kubernetes: `./run_kubernetes.sh`

### Kubernetes Steps

-   Setup and Configure Docker locally
-   Setup and Configure Kubernetes locally
-   Create Flask app in Container
-   Run via kubectl



## Mentions:
- The libraries are outdated and so it will not make predictions. If you choose to extend, you will have to sort
through the ML libraries and update wherever necessary. This is intended as a base model. :) Extend as you want.