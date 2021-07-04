`mget name language`

```
MULTI
set name Tim

set language Python

EXEC
```

`mget name language`

`flushall`

`mget name language`

```
MULTI
set name Dave
set age 47
lpop name
set language Java
EXEC
```

`mget name age language`

```
MULTI
set language Rust
DISCARD
```

`get language`

`set count 1`

`get count`

`get count`

`WATCH count`

```
MULTI
set count 100
```

`set count 5`

`EXEC`

`get count`
`get count`
