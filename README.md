
# Welcome to the README file for CLO835 Assignment 2!

This assignment is done  Asif Raja

## Assignment 2 Title:

## Create K8s cluster, deploy containerized stateless applications using K8s manifests, expose the applications as NodePort services, roll out an updated version of the application 

## Table of Contents
- [ Using git action to create and push the webserver and database image to Amazon ECR ]
- [ Using K8s manifest file to deploy webserver and database ]
- [ Running single node kind cluster on EC2 ]
  



## Using git action to create and push the webserver and database image to Amazon ECR


## Using GitHub action

Instructions on using GitHub action.
- Work on your application code and mysql code and docker files in staging branch 
- git add .
- git commit -m "commit "
- git push 
- Git action is triggered as follows:
- Docker workflow will trigger on any push or pull_request on main branch
- Webserver and databsae image will be pushed to ECR

## Using EC2 instance to host the application and database container

Instruction on using EC2 instance to run docker containers
- SSH to  the EC2 instance and install the Kind cluster.
- Goto to K8s dirctory where the manifest file are stored
- Run the manifest file one bye in proper oder to deploy MSQL and Webserver

-
