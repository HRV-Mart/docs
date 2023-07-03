---
layout: default
title: Architecture
nav_order: 3
has_children: true
---

# HRV-Mart Architecture

In this section, we will see about the architecture of HRV-Mart application.

## Overview

![HRV-Mart Architecture](https://github.com/HRV-Mart/docs/assets/55652117/573d7a5c-a5cd-473e-8840-ad4160281296)

In above image, you can see that their is a dependency between components. If you want to work on, let say, `Front-End` then you have to make sure that all components of `API-Gateway` and `Back-End` are working.

{: .note } While running any component, you need database, Kafka and appwrite running in background.
