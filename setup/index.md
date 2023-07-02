---
layout: default
title: Set-Up Project
nav_order: 2
has_children: true
---
# Project Set up

Depending on the type of repository you are working, setting up project may vary. But their are some common components which you need to install before setting up whole environemnt.

## Step-1 Install Git

You need to install [git](https://git-scm.com/) inorder to do changes in code-base

## Step-2 Create a GitHub account

Create and setup your [GitHub](https://github.com/) account.

## Step-3 Install docker

Install [Docker](https://www.docker.com/). Docker will allow you to pull dokcer images and run containers in your local environment.

## Step-4 Set-Up Kafka

There are two ways to set it up

### Option-A: Installing Kafka

[Visit Kafka website](https://kafka.apache.org/downloads)
In order to run kafka, you also need [Zookeeper](https://zookeeper.apache.org/).

### Option-B: Use Docker to install Kafka

You mentioned guide to setup kafka with zoopeeker using docker
[how-to-start-kafka-using-docker- by conduktor.io](https://www.conduktor.io/kafka/how-to-start-kafka-using-docker/)

## Step-5 Set-Up Mongo-DB

There are three ways to set it up

### Option-A: Installing Mongo-DB

[Download mongodb community version](https://www.mongodb.com/download-center/community/releases)

### Option-B: Use Docker to install Mongo-FB

```cmd
docker run --name mongodb -d -v DATABASE/DIRECTORY:/data/db -p 27017:27017 mongo
```

Here, `DATABASE/DIRECTORY` is path to the directory where you want to store mongo db data

After doing this basic set-up, you can proceed to the repository specific set-up

### Option-C: User Mongo Atlas

[MongoDB Atlas Link](https://www.mongodb.com/atlas)
