# Multi-Docker
The purpose of the project is calculate the Fibonacci Sequence at specific indexes, and to display the returned value, alongside the inputted value.  

This is a project created during Docker and Kubernetes: The Complete Guide course. Created using the React.js framework and leverages the offical docker containers such as Redis and Ngnix, as well as custom docker containers created through the local folders.

## Hosting 
This project was design to run of Amazon Web Services (AWS) using the following services:
- ElasticBeanstalk
- VPC
- RDS
- ElastiCache
- RDS
- S3
- IAM

## Testing
This project was tested and deployed with Travis CI.

## Running the file
To run the file it would require many changes as there is no current deployment on a hosting platform. However, if the correct changes were made it can be started by
1. running `docker-compose up --build` in the client, nginx, server, and worker file.
2. running `docker-compose -f docker-compose-dev.yml up --build` in the main directory. 