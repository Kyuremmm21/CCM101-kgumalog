# Laboratory 06 – Cloud Deployment Engineer

## Mission Overview
In this laboratory, we deployed a multi-container private cloud storage system using Nextcloud and MariaDB with Docker Compose. This demonstrates Infrastructure as Code (IaC) by defining the entire stack in a YAML file.

## Objectives
- Explain multi-tier application architecture
- Understand and write a docker-compose.yml file
- Deploy a multi-container application using Docker Compose
- Document Infrastructure as Code principles
- Expand the Cloud Computing Portfolio on GitHub

## Commands Executed
```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
