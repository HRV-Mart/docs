---
layout: default
title: Setting up API-Gateway
parent: Set-Up Project
has_children: false
---

# Setting up API-Gateway

Currently, HRV-Mart have two API-Gateway which are:

- [API-Gateway](https://github.com/HRV-Mart/API-Gateway): It is created for users with `USER` role.
- [Admin-API-Gateway](https://github.com/HRV-Mart/Admin-API-Gateway): It is created for users with `USER` role.

For both of them, you need to follow below option.

## Step-1: Create Appwrite credentials

For authentication purpose, HRV-Mart uses [Appwrite](https://appwrite.io/). So, you need to create a project in appwrite. You will going to use it in `Backend-Auth`. Make sure you also generate am API-Key for that project.

## Setp-2: Pull and run docker images of Backend

- [Set-up Backend-Auth](https://github.com/HRV-Mart/Backend-Auth#set-up-application-using-docker)
- [set-up Backend-Product](https://github.com/HRV-Mart/Backend-Product#set-up-application-using-docker)
- [Set-up Backend-User](https://github.com/HRV-Mart/Backend-User#set-up-application-using-docker)
- [Set-up Backend Order](https://github.com/HRV-Mart/Backend-Order#set-up-application-using-docker)
- [Set-up Backend-Cart](https://github.com/HRV-Mart/Backend-Cart#set-up-application-using-docker)
- [Set-up Backend Like](https://github.com/HRV-Mart/Backend-Like#set-up-application-locally)
- [Set-up Backend-Review](https://github.com/HRV-Mart/Backend-Review#set-up-application-using-docker)

## Step-3 Install any API-testing software

Install any API-testing software like [Postman](https://www.postman.com/)
