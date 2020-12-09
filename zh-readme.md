# 使用 Redis 构建轻量级 Microservices

`Hydra` 是一个轻量级的 NodeJS 库，用于构建分布式计算应用程序，比如微服务。我们对轻量级的定义是：轻处理外部复杂性和基础设施依赖 —— 而不是有限的轻处理。
`Hydra` 声称对基础设施的依赖很轻，这是因为它唯一的外部依赖是 `Redis`。

Hydra 利用 Redis 丰富的数据结构来实现重要的微服务所需的功能。
如 `presence`（在线状态）、`service discovery` （服务发现）、`load balancing` （负载平衡）、`messaging`（消息传递）、`queuing`（队列）等。

### Hydra 到底是什么？