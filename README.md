# Project: Image Processing Microservice on AWS

You have been hired as a software engineer to develop an application that will help the FBI find missing people. The application will upload images to the FBI cloud database hosted in AWS. This will allow the FBI to run facial recognition software on the images to detect a match. You will be developing a NodeJS server and deploying it on AWS Elastic Beanstalk.

You will build upon the application we've developed during the lessons in this course. You'll complete a REST API endpoint in a backend service that processes incoming image URLs.

***
## Getting Setup

### Installing project dependencies

This project uses NPM to manage software dependencies. NPM Relies on the package.json file located in the root of this repository. After cloning, open your terminal and run:
```bash
npm install
```
>_tip_: **npm i** is shorthand for **npm install**

***

## Running the Server Locally
To run the server locally in developer mode, open terminal and run:

`npm run dev` 


#### Test URL
http://localhost:8082/ - locally
http://assignment-dev.us-east-1.elasticbeanstalk.com/ - aws hosted


## Curl commands

#### Process Kitten Image
```
curl --location 'http://assignment-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg'
```
