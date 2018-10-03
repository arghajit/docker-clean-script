# docker-clean-script

While we work with Docker containers, it sometime occur that our host machine start getting low memory. 

A simple shell script to clear all hibernated/slept/down images/containers/networks to free up the space.

## Run
```
arghajit@mac$ chmod a+rx docker-cleanup
arghajit@mac$ ./docker-cleanup
```

Add it in your path to use it across any location.
