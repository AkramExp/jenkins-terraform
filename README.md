
# Terraform Integration into Jenkins



## Description

A DevOps project made by **Jenkins CI/CD, Terraform, Docker, Shell Script, AWS.**

Terraform is a tool to automate the infrastructer provisioning by writing Terraform files and spinning up servers in few seconds without doing the repetetive task of provisioning servers manually.


- A java maven app is build with maven command.
- After the building the jar artifact, A docker image is build with it and pushed into the dockerhub repository.
- EC2 instance on AWS Cloud is provisioned with Terraform files.
- After provisioning the server with terraform the server IP is fetched into Jenkins with the Terraform output command.
- SSH into AWS server from Jenkinsfile and prepare the server with shell script to deploy application.
- After running the shell script the docker image is fetched from dockerhub repository and run with docker command.

## Project Flow Chart
![ss1](https://github.com/AkramExp/jenkins-terraform/blob/main/screenshots/ss1.png)
