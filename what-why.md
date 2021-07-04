Redis - Remote Dictionary Server
in-memory key-value data structure store, used as a database, cache, and message broker

delivers sub-millisecond response times enabling millions of requests per second.

Real time apps in Gaming, Ad-Tech, Financial Services, Healthcare, and IoT.
Redis is a popular choice for caching, session management, gaming, leaderboards, real-time analytics, geospatial, ride-hailing, chat/messaging, media streaming, and pub/sub apps.

How does Redis work?
All Redis data resides in-memory
rather than storing data on disk or SSDs like PG, mongo etc.
By having in-memory data stores Redis aims to avoid time delays and can access data in microseconds.

Redis features:

- versatile data structures
- high availability
- geospatial
- transactions
- on-disk persistence
- cluster support making it simpler to build real-time internet scale apps.

Pros:

- in-memory data store - makes it blazingly fast
- flexible data structures
- simple & easy to use
- high availability & scalability
- Replication & persistence
- Extensible

Install

- via https://redis.io/download
- then run `redis-server`

- via docker
- `docker run -p 6379:6379 --name rediscrashcourse redis:latest`
- then `docker exec -it rediscrashcourse redis-cli`
