# CICD
**CICD — Continuous Integration and Continuous Delivery and Deployment**

## Continuous Integration (CI)

Developers merge/commit code to master branch multiple times a day, fully automated build and test process which gives feedback within few minutes, by doing so, you avoid the integration hell that usually happens when people wait for release day to merge their changes into the release branch.

![image](https://user-images.githubusercontent.com/94615905/145240423-71ee0108-5cb3-497d-b97b-46e5fa7efa88.png)

## Continuous Delivery (CD)

An extension of continuous integration to make sure that you can release new changes to your customers quickly in a sustainable way. This means that on top of having automated your testing, you also have automated your release process and you can deploy your application at any point of time by clicking on a button. In continuous Delivery the deployment is completed manually.

![image](https://user-images.githubusercontent.com/94615905/145240928-7bb9a509-8c94-4ba2-a594-1ece3757fd63.png)

## Continuous Deployment 

Goes one step further than continuous delivery, with this practice, every change that passes all stages of your production pipeline is released to your customers, there is no human intervention, and only a failed test will prevent a new change to be deployed to production.

![image](https://user-images.githubusercontent.com/94615905/145248808-4c15783b-3a8a-435b-827c-0920d8554429.png)

## CICD Workflow

![image](https://user-images.githubusercontent.com/94615905/145251130-fcadbeeb-1d23-446e-9f85-6695972420c9.png)

## How CICD Practices relate to each other 

To put it simply, the continuous integration is part of both continuous delivery and continuous deployment. The main difference is the deployment step, in continuous delivery the deployment is done manually and in continuous deployment it happens automatically.

## What is a CICD Pipeline
The CICD pipeline is all about automation: Initiating code builds, automated testing, and automated deploying to the staging or production environments. It’s complex and exciting at the same time, but incredibly fast, if the output of any stage fails, the next stage will also fail.

## CICD Tools to build Pipeline

![image](https://user-images.githubusercontent.com/94615905/145251531-ebc97643-d55d-4a73-9157-c7616c908161.png)


# Jenkins

> Jenkins is an open-source automation server in which the central build and CI process take place, It is a Java-based program with packages for Windows, macOS, & Linux.

>Jenkins helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery. It is a server-based system that runs in servlet containers such as Apache Tomcat.

> In Jenkins a task is called a job

**Jenkins pipeline diagram**

![image](https://user-images.githubusercontent.com/94615905/145247570-c9a92e21-661f-4ce6-8c94-f4ac091ef1a4.png)


