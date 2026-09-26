# AWS Academy Lab Project – Microservices and CI/CD Pipeline Builder

## Overview

This project was completed as part of the AWS Academy Lab Project:
Building Microservices and a CI/CD Pipeline with AWS.

The lab involved transforming a monolithic Coffee Suppliers application
into separate customer and employee microservices and deploying them using
a container-based AWS architecture.

## AWS Services Used

- AWS Cloud9
- AWS CodeCommit
- Amazon ECR
- Amazon ECS
- AWS Fargate
- Application Load Balancer
- AWS CodeDeploy
- AWS CodePipeline

## Microservices

### Customer Microservice
Handles the customer-facing functionality of the Coffee Suppliers application.

### Employee Microservice
Handles the employee/administrator functionality of the application.

## Deployment

The microservices were containerized using Docker and deployed to
Amazon ECS using AWS Fargate.

An Application Load Balancer was configured to route requests to the
appropriate microservice.

AWS CodeDeploy was used for blue/green deployments, and AWS CodePipeline
was configured to automate the deployment process.

## Evidence

The repository contains the available source code, deployment configuration
files, and supporting documentation for the completed AWS Academy lab.

## Lab Completion

The deployed Coffee Suppliers application was successfully accessed through
the Application Load Balancer and tested after deployment.
