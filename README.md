[![CircleCI](https://circleci.com/gh/ISafronenko/project-ml-microservice-kubernetes/tree/master.svg?style=svg)](https://circleci.com/gh/ISafronenko/project-ml-microservice-kubernetes/tree/master)

## Project Overview

This project is about creation of simple Flask application to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on.


## Setup the Environment

* Create a virtualenv and activate it: `python3 -m venv ~/.devops`
* Run `make install` to install the necessary dependencies or run
```
pip install --upgrade pip &&\
		pip install -r requirements.txt
```

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
