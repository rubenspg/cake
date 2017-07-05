# Deployment of Wordpress and ELK using Ansible

## Description

This repository contains an example of deployment on AWS using Ansible.
The applications will be:
  - Wordpress with Nginx
  - ELK stack to monitor the Wordpress application

## Installation
The following tools/applications are required to develop or run this project:
  - Ansible (if you don't have yet use this [link to install](http://docs.ansible.com/ansible/intro_installation.html))
  - [AWS Account](https://aws.amazon.com/)
  - [Python 2.7+](https://www.python.org/download/releases/2.7/)
  - [Docker](https://docs.docker.com/get-started/)

The used Docker images are from:
  - WordPress: https://hub.docker.com/_/wordpress/

## Usage

## Tasks
 - [ X ] Task 1: Install and investigate how to use Ansible   
 - [  ] Task 2: Create docker-compose for ELK
 - [  ] Task 3: Provisioning AWS infrastructure to run ELK using Ansible
 - [  ] Task 4: Create docker-compose for Wordpress + Nginx application
 - [  ] Task 5: Deploy dockerized WordPress based blogging application using Ansible
 - [  ] Task 6: Monitor the AWS resources and the blogging application using you ELK
 - [  ] Task 7: (Stretch Goal) Prepare an insightful dashboard

## How to contribute

You are welcome to contribute. Just follow these steps:

### Clone or fork the repository

```
git clone git@github.com:rubenspg/cake.git
```

### Do some work

```
git checkout master
git pull origin master
git checkout -b contrib/branch_name
```

### Execute the tests

Before you commit and push your changes, run the tests to make sure everything is working. For docker-compose files, just run:
```
docker-compose up
```

### Create a PR
```
git push -u origin contrib/branch_name
