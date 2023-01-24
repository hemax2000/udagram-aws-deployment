# Hosting a Full-Stack Application


In this project you will learn how to take a newly developed Full-Stack application built for a retailer and deploy it to a cloud service provider so that it is available to customers. You will use the aws console to start and configure the services the application needs such as a database to store product information and a web server allowing the site to be discovered by potential customers. You will modify your package.json scripts and replace hard coded secrets with environment variables in your code.

After the initial setup, you will learn to interact with the services you started on aws and will deploy manually the application a first time to it. As you get more familiar with the services and interact with them through a CLI, you will gradually understand all the moving parts.

You will then register for a free account on CircleCi and connect your Github account to it. Based on the manual steps used to deploy the app, you will write a config.yml file that will make the process reproducible in CircleCi. You will set up the process to be executed automatically based when code is pushed on the main Github branch.

The project will also include writing documentation and runbooks covering the operations of the deployment process. Those runbooks will serve as a way to communicate with future developers and anybody involved in diagnosing outages of the Full-Stack application.

# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

----------------------------------------------

you can see view the project at: http://udagram-4095-0013-6750.s3-website-us-east-1.amazonaws.com

## Dependencies


- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2

- A RDS database running Postgres.

- A S3 bucket for Frontend static pages.

- A EB for hosting Website APIs



## Screanshots

#### S3 Bucket

<img width="1080" alt="image" src="https://user-images.githubusercontent.com/95032871/214298993-28bebc72-aed3-4ae7-9a09-4053a314e232.png">


#### EB

<img width="1080" alt="image" src="https://user-images.githubusercontent.com/95032871/214299204-171a3338-5721-4ea3-af63-0cdfa0d57ad8.png">

#### RDS 

<img width="1080" alt="image" src="https://user-images.githubusercontent.com/95032871/214299954-63ca6e8a-0002-4883-b0c8-5be712dbaf7e.png">


#### CircleCI Pipeline

<img width="1079" alt="image" src="https://user-images.githubusercontent.com/95032871/214301336-dfd345dd-e41f-4f57-a9ae-9498e40ffcdd.png">

- build

<img width="1080" alt="image" src="https://user-images.githubusercontent.com/95032871/214301725-13a83310-0b93-4382-8e52-859c63314ddf.png">

<img width="1080" alt="image" src="https://user-images.githubusercontent.com/95032871/214302128-d5319ba3-8d59-4b3d-9311-c00c9ba37c2e.png">


- deploy

<img width="1077" alt="image" src="https://user-images.githubusercontent.com/95032871/214302338-e722b863-3cb1-405c-b2f7-b286ea7fba77.png">


- ENV 

<img width="1080" alt="image" src="https://user-images.githubusercontent.com/95032871/214302857-3bc5dd9d-cb63-4619-baee-43fc6fb92bc4.png">

---------------------------------------------

#### AWS proccess

<img width="375" alt="image" src="https://user-images.githubusercontent.com/95032871/214306756-9e76fdb2-0a74-4851-98b4-cd5aed4e73b4.png">


#### pipeline proccess

![pipeline](https://user-images.githubusercontent.com/95032871/214308228-7173d220-70d7-407d-a97b-f5b09f3264db.jpg)

