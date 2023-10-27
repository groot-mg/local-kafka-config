# Local Kafka config

This repository contains configuration to run Kafka on local environment.

It is possible to run the `docker-compose.yml` via command line with the command:

```shell
docker-compose up
```

It will start the `zookeeper`, `kafka` and `kafdrop`.

## kafka

Kafka depedenps on Zookeeper to run, and will be available on the port `http://localhost:9092`

## Kafdrop

[Kafdrop](https://github.com/obsidiandynamics/kafdrop) is a kafka UI to see kafka informations in a webpage. 

It will be available on [http://localhost:9021](http://localhost:9021)


## Run together with the project
Kafka is one of the dependencies for the services in the `groot-mg project`, to run all the services together, please see [docker-local-setup](https://github.com/groot-mg/docker-local-setup).