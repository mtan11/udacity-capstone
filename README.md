[![CircleCI](https://dl.circleci.com/status-badge/img/gh/mtan11/udacity-capstone/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/mtan11/udacity-capstone/tree/main)
# Cloud DevOps Engineer Capstone Project
This project represents the successful completion of the last final Capstone project and the Cloud DevOps Engineer Nanodegree at Udacity.
URL: http://ae6dfecc55c1548c4bdc31a55984fbd6-830603826.us-east-1.elb.amazonaws.com/index
# Project Overview
In this project, I use all skill that I learn in this course to do. Just use a simple flask app to practice devops skill. This will use aws-eks to deploy the source code.

- In a CircleCI pipeline, we lint the project's code, build a Docker image and deploy it to a public Docker Registry: Docker Hub
- Then in an AWS EKS cluster, we run the application
- Later, we promote to production a new app version using a rolling update strategy

## PROJECT SPECIFICATION
- Create Github repository with project code.
- Use image repository to store Docker images
- Execute linting step in code pipeline
- Build a Docker container in a pipeline
- The Docker container is deployed to a Kubernetes cluster
- Use Blue/Green Deployment or a Rolling Deployment successfully

# Project Tasks
- Check lint issue
- Build docker image and push it
- Deploy infrastructure
- Smoke test
In the end, the app is deployed to the cluster and accessible to users.

# Tools that I used to build the project
- Python
- AWS
- Docker
- Kubernetes