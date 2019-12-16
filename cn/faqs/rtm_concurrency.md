
---
title: RTM 对同时在线人数是否有限制？单个频道内并发人数可以支持到多少？
description: 
platform: All Platforms
updatedAt: Thu Aug 29 2019 19:00:55 GMT+0800 (CST)
---
# RTM 对同时在线人数是否有限制？单个频道内并发人数可以支持到多少？
Agora RTM SDK 对于并发人数以及单频道并发人数的支持没有上限。
- 如果单频道并发人数低于 1000 人，建议把该频道的消息数控制在每秒 200 条以内；
- 如果低于 10000 人，建议把该频道的消息数控制在每秒 100 条以内；
- 如果单频道人数超过 10000 人，建议把该频道的消息数控制在 30 条以下，并请联系我们的支持团队沟通具体使用场景。