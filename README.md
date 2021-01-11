# Udacity-Cloud-DevOps-Engineer-Capstone-Project

### Capstone project for Udacity's Cloud DevOps Nanodegree

The goal of the project is to set up a Kubernetes cluster using AWS Elastic Kubernetes Service to deploy a docker image leveraging Jenkins CI/CD Pipeline.

## Project Info
A simple python app, app.py was created using Flask that displays a web page. This simple app was created to illustrate how apps can be contanerized with docker and used as microservice with the use of kubernetes.

## Branches
master => This branch contains the latest code that is running is production. So this could be from green or blue branch blue => This branch contains code for implementing blue/green deployment. green => This branch contains code for implementing blue/green deployment

## Deployment type
This project implements a solution for blue/green deployment to achieve a zero-dowmntime deployment. /CloudFormation/Udacity DevOps Capstone project.pdf shows a high-level diagram for this implementation