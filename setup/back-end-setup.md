---
layout: default
title: Setting up Back-end
parent: Set-Up Project
has_children: false
---


# Setting up Back-end

There are total seven repository which falls under `Backend` category. Repositories are:

- [Backend-Auth](https://github.com/HRV-Mart/Backend-Auth#set-up-application-using-docker): This repository handles task related to `Authentication`
- [Backend-Product](https://github.com/HRV-Mart/Backend-Product#set-up-application-using-docker): This repository handles task related to `Product`.
- [Backend-User](https://github.com/HRV-Mart/Backend-User#set-up-application-using-docker): This repository handles task related to `User`.
- [Backend Order](https://github.com/HRV-Mart/Backend-Order#set-up-application-using-docker): This repository handles task related to `Order`.
- [Backend-Cart](https://github.com/HRV-Mart/Backend-Cart#set-up-application-using-docker): This repository handles task related to `Cart`
- [Backend Like](https://github.com/HRV-Mart/Backend-Like#set-up-application-locally): This repository handles task related to `Like`
- [Backend-Review](https://github.com/HRV-Mart/Backend-Review#set-up-application-using-docker): This repository handles task related to `Review`

{: .note }
> `Backend-Auth` uses [Appwrite](https://appwrite.io/) to authenticate user.

{: .note }
> `Backend-User`,`Backend-Auth`, `Backend-Cart` and `Backend-Order` uses Kafka. In order to setup kafka, [uses this guide](/setup/#step-4-set-up-kafka)

Steps to set up repository.

## Step-1: Choose an IDE

You can use any IDE which support spring boot development like vscode.

## Step2: Install Gradle and Java

Recomendation: Use [SDK Man](https://sdkman.io/) to install and change version of Java and Gradle.

## Step-3 Install any API-testing software

Install any API-testing software like [Postman](https://www.postman.com/)
