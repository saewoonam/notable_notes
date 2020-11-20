---
tags: [docker, node, redis, web fridge]
title: Todo for node based fridge control
created: '2020-11-15T15:39:06.505Z'
modified: '2020-11-19T17:39:38.290Z'
---

# Todo for node based fridge control

* try node docker contanier
* design state machine
  - java-state-machine(https://github.com/jakesgordon/javascript-state-machine)
  - jssm (https://github.com/StoneCypher/jssm)
  - fsm-as-promised (https://github.com/vstirbu/fsm-as-promised)
  - fsm-iterataor (https://github.com/jfairbank/fsm-iterator)
* decide number of docker containers
  - server for instruments
  - state machine
  - redis
  - web
  - logger

## things that are done
* redis:  docker start my-redis
  -  used:  ```docker run --name my-redis -p 6379:6379 redis:alpine```
