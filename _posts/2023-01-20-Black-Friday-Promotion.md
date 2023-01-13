---
title: "Black Friday Promotion"
layout: post
---
- Completed migrating and separating Order service to Promotion and Order microservices for Black Friday project, peak load shifting to deal with high concurrency scenarios by Redis and RocketMQ.
- Implemented cache preheating, lock inventory and purchase limit functions by Redis with Lua script.
- Optimization query and update by MySQL optimistic locking.
- Released the stress of Order service by asynchronously creating orders by RocketMQ.
- Implemented check order status, and cancel orders by RocketMQ delay message queue.

<img width="1072" src="https://user-images.githubusercontent.com/105135459/210188251-687198e3-3db0-40d3-b748-0de9aeb4a29a.png">

[Show project](https://github.com/Huicccc/Black-Friday-Promotion-and-Order)
