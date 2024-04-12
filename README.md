The aim of project is how to make your website as dynamic website instead of static website

In this project, I utilized various AWS services to achieve my goal:

S3: Used to host the website and store static assets.
AWS API Gateway: Implemented as the entry point for the website, enabling communication between the frontend and backend.
AWS DynamoDB: Leveraged as the database to store and manage user information.
AWS Lambda Functions with Python Scripts: Developed custom Lambda functions to handle different API Gateway methods, including registration, user deletion, and retrieving all users.
Flutter Framework: Utilized to build the frontend of the website, creating a seamless user interface.
AWS CodeCommit: Employed as the repository to manage version control for the project.
AWS Amplify: Utilized for provisioning, building, testing, and deploying the application, ensuring a streamlined CI/CD process.


Flow :
first the user will be use website to record information like email and name and phone
and then the website will send request for AWS Api Gateway methods:
1- Post
2- Get
3- Delete
and then AWS Api Gateway will call Lambda functions from:
1- Register
2- Delete User
3- Get All users

and then the lambda function will deal with DynamoDB database for delete update, or get data

also i use CodeCommit instead of GitHub to make repo

and finally i use AWS Ampilfy to provision,build ,test, and deploy(CI/CD)
codeCommit-repo:
https://git-codecommit.eu-west-1.amazonaws.com/v1/repos/DevOps-Guide

DevOps-Guide website:
https://master.d3fqbc0no6y1wy.amplifyapp.com

