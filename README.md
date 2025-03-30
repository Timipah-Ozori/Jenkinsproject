# Jenkinsproject

## Project Objective;

1. Jenkins server setup and configuration for CI/CD pipeline automation.
2. Source code management  repository integration with Jenkins 

3. Jenkins freestyle Job and unit test. 
4. Jenkins Pipeline for a running web application. 

5. Docker image Creation  and Registry Push 


## Project Requirements;

1. Compute: AWS EC2 Instance for hosting jenkins 
2. Creation of Security Groups to allow SSH and HTTP traffic 

## STEPS;

## Created an Instance on AWS for Jenkins server 

![](./img/1.%20Jenkins%20server.png)

Allow SSH Traffic 

![](./img/7.SG.png)

## Connect ing to the server via SSH

![](./img/2.%20ssh%20to%20server.png)

## Installing necessary dependencies 

`sudo apt update`

![](./img/3.%20sudo%20apt.png)

![](./img/3.%20sudo%20apt%202.png)

`sudo apt install jdk`
![](./img/4.%20JDK.png)


![](./img/4.%20JDK%202.png)

## Install Jenkins

`Sudo apt-get install Jenkins `

![](./img/5.%20install%20jen.png)

## Jenkins is running 

![](./img/6.%20sudo%20system.png)

## Getting started, Unlock Jenkins 

![](./img/8.%20Getting%20started.png)

## Cat Password for Jenkins 

![](./img/9.%20cat%20password.png)

## Customise Jenkins 

![](./img/9.%20Customize%20Jenkins.png)

![](./img/10.%20Getting%20started.png)

## Setting up Admin User 

![](./img/11.%20First%20Admin%20User.png)

## Instance Configuration

![](./img/12.%20Instance%20config.png)


## Jenkins is Ready

![](./img/13.%20Jenkins%20is%20ready.png)


## Pluggin 
![](./img/14.%20plugin.png)

![](./img/14.%20plugin%202.png)

![](./img/14.%20plugin%203.png)


## Source Code Management 

![](./img/15.%20scm%201.png)

![](./img/15.%20scm%202.png)


## Trigger 

![](./img/18.%20trigger.png)




##  Created a Freestyle Job

![](./img/21.freestyle%20job.png)

![](./img/22.freestyle%20job%20success.png)

![](./img/22.freestyle%20job%20success%202.png)


## Freestyle Trigger 

![](./img/22.freestyle%20job%20triggers.png)

![](./img/22.freestyle%20job%20triggers%202.png)

![](./img/22.freestyle%20job%20triggers%203.png)


## Before editing the Read ME file to test Trigger 
![](./img/23.%20Read%20me%20file.png)


## The Edited READ ME file 

![](./img/23.%20Read%20me%20file%20edit.png)


## Trigger Succeeded 
![](./img/24.%20trigger%20success.png)

![](./img/24.%20trigger%20success%202.png)


##  Overview 
![](./img/25.%20overview.png)



##  Docker Installation

![](./img/26.%20docker%20install.png)


![](./img/26.%20docker%20install%202.png)

![](./img/26.%20docker%20install%203.png)

![](./img/26.%20docker%20sh.png)


![](./img/27.%20Dockerfile%20created.png)


![](./img/27.%20Dockerfile.png)


## Index File

![](./img/28.%20index.html%20file.png)

## Push Index File to Github

![](./img/30.%20push.png)


## Setting Up Global Credentials 

![](./img/16.%20global%20cred.png)


## Pipeline 

![](./img/17.%20pipeline.png)

## Trigger 

![](./img/18.%20trigger.png)

## Pipeline Syntax

![](./img/19.%20pipeline%20syntax.png)

![](./img/19.%20pipeline%20syntax%202.png)

## Pipeline Script

![](./img/20.%20pipeline%20script.png)

![](./img/20.%20pipeline%20script%202.png)

![](./img/31%20.%20build%201.png)


![](./img/32%20.%20build%20output%201.png)

![](./img/32%20.%20build%20output%202.png)

![](./img/32%20.%20build%20output%203.png)

![](./img/32%20.%20build%20output%204.png)

![](./img/32%20.%20build%20output%205.png)

![](./img/32%20.%20build%20output%206.png)


## Docker Hub Push to Repository Successful

`Jenkins-webappproject`

![](./img/33.%20Docker%20hub.png)

![](./img/33.%20Docker%20hub%202.png)


![](./img/33.%20Docker%20hub%203.png)


## Edited Index File for Website 

![](./img/34.%20test%20edit%20on%20index%20file.png)


## Allowed http acccess of Jenkins server instance
 ![](./img/35.%20sg%20allow.png)


## Accessing website with Ip address and port

![](./img/36.%20website%20accessible.png)


# Overview of Successful Jenkins Jobs 

![](./img/37.%20done.png)