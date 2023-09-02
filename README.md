# Hosting a Full-Stack Application

### **The project is part of udacity-fullstack nano-degree and need approvel from udacity to be used**

---

this project was provided as a completed project and my task was to deploy the project and prepare it for deployment and being used.

in this project i used AWS and its' services in order to finish the task, though a workflow. the workflow starts with making and admin account to control the poject and process. second, i needed to make a buscket and database using RDS and S3

After that, i need to use eb to upload, deploy the project. with modified package.json the web is deployed and ready to be used

Using CircleCi connected to repo of the project on github gave circleci the potential to track my changes during the work on the project

## To visit the web site [Site](http://hamza-udagram.s3-website-us-east-1.amazonaws.com) 


This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

#### diagram of cloud infrastucture
![Infra cloud](./screenshots/diagram.png)

# Documentation: 
1- [Infrastructure](./documentation/infrastructure.md)
2- [Installation](./documentation/installation.md)
3- [A way to start](./documentation/a-way-to-start.md)
4- [Dependencies](./documentation/dependencies.md)
5- [CI/CD](./documentation/cicd.md)

## Screenshots
---
#### RDS(database)
![RDS](./screenshots/RDS.jpg)

#### Elastic Beanstack
![EB](./screenshots/eb.jpg)

#### S3 (bucket)
![S3](./screenshots/s3.jpg)

#### CI/CD
![CI/CD](./screenshots/success-circleci.jpg)

## License

[License](LICENSE.txt)
