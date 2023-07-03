---
layout: default
title: Back-End Architecture
parent: Architecture
nav_order: 1
has_children: false
---

# Back-End Architecture

This section contains how backend layer works. All backend repository listed under HRV-Mart are using [Spring-Boot reactive](https://spring.io/reactive), [Kotlin](https://kotlinlang.org/) and [Gradle](https://gradle.org/).
All backend repositories are listed below.

- [Backend-Auth](https://github.com/HRV-Mart/Backend-Auth)
- [Backend-Product](https://github.com/HRV-Mart/Backend-Product)
- [Backend-User](https://github.com/HRV-Mart/Backend-User)
- [Backend Order](https://github.com/HRV-Mart/Backend-Order)
- [Backend-Cart](https://github.com/HRV-Mart/Backend-Cart)
- [Backend Like](https://github.com/HRV-Mart/Backend-Like)
- [Backend-Review](https://github.com/HRV-Mart/Backend-Review)

In ordere to communicate with other micor-services, they use Rest-API calls or Kafka. To make communication between them easier, libraries are created. 
Those libraries are:

- [product](https://github.com/HRV-Mart/product)
- [auth-library](https://github.com/HRV-Mart/auth-library)
- [user-library](https://github.com/HRV-Mart/user-library)
- [cart-response](https://github.com/HRV-Mart/cart-response)
- [order-library](https://github.com/HRV-Mart/order-library)

In order to use pagination, [Custom-Pageable](https://github.com/HRV-Mart/Custom-Pageable) is creted.
For calling an API, use [API-Call](https://github.com/HRV-Mart/API-Call)
