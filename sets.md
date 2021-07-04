`sadd fruits Apple`

`smembers fruits`

`sadd fruits Pear Blueberry Strawberry Fig Cabbage`

`srem fruits Cabbage`

Sets only contain unique values so if you add the same value again you will get back 0 and nothing will change
`sadd fruits Pear`

get the number of members within a set
`scard fruits`

`sismember fruits Fig`

`sismember fruits Basil`

`sadd red-fruits Apple Strawberry Cherries`

`sdiff fruits red-fruits`

`sdiffstore non-red-fruits fruits red-fruits`

`sinter fruits red-fruits`

`sunion fruits red-fruits`

`sunionstore all-fruits red-fruits`

`sadd vegetables Cabbage`

`sadd fruits Lettuce`

`smove fruits vegetables Lettuce`
