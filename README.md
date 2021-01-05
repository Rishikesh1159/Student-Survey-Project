# Student-Survey-Project
Project Description:
--> This is a front end angular web application which has a student form and connects with backend using Rest Web Services. 
--> This application has created with the mappings for Rest Api’s using Springboot as a backend. JPA is used to connect with Database Amazon.
--> It established a CI/CD pipeline that include a GitHub as a source code repository and the build automation tool Jenkins, and the Kubernetes platform for the automated build and deployment of our application.


Steps to Start:
-->Download the project folder from github.
-->Download and install Lastest versions off Java and CLI.
-->If possible download and install angular CLI.
-->Create and start RDS Mysql database and put those details in your RDS details in springboot. 
-->Open Springboot part of application and run the application.
-->Open Angular part of application and start the application.
-->Make sure you can successfully run application in your local machine.
-->Now Install docker on your Machine and create images for both front-end and back-end application individually.
-->Push the images to our docker repository
-->Using EKS create a kubernetes cluster.
-->Deploy both front-end and back-end from docker hub to cluster using loadbalancers.
-->Yaml files for deployment are provided in project folder.
-->Now access your application with loadbalancers public address.
