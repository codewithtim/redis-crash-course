# Strings

`docker run -p 6379:6379 --name rediscrashcourse redis:latest`

https://redis.io/commands#string

`set name Tim`

`get name`

`set email codewithtim@gmail.com`

`strlen email`

`mset age 31 channel codewithtim`

`mget name email`

`getrange email 0 5`

`getrange email 0 -1`

`set count`

`get count`

`incr count`

`decr count`

`incrby count 5`

`decrby count 5`

`setnx Dave`

`setex expireme 10 "Do I exist?"`
