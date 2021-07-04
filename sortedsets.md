`zadd leaderboard 1 Dave`

`zadd leaderboard 2 Tim 3 Sarah 4 Pete 5 Kate 5 Steve`

`zrange leaderboard 0 -1`

`zrange leaderboard 0 -1 withscores`

`zcard leaderboard`

`zcount leaderboard -inf +inf`

`zadd leaderboard 1 Python`

`zrem leaderboard Python`

`zrange leaderboard 0 -1`

`zrange leaderboard 0 -1 withscores`

`zrevrange leaderboard 0 -1 withscores`

`zscore leaderboard Pete`

`zrangebyscore leaderboard`

`zincby leaderboard 1 Tim`

`zincby leaderboard -1 Sarah`

`zremrangebyscore leaderboard 5 5`
