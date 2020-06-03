# TICK-Docker-Starter-Kit

TICK stack on containers with are ready to use.

## Folder structures

| Path            | More details          |
|-----------------|-----------------------|
| telegraf/conf   | Store config files    |
| influxdb/data   | Store influxdb data   |
| chronograf/data | Store chronograf data |
| kapacitor/data  | Store kapacitor data  |

## Create and start containers

To start a stack just type

```bash
$ docker-compose up -d
```

## Start services

Start TICK services

```bash
$ docker-compose stop
```

## Stop services

Stop TICK services

```bash
$ docker-compose stop
```

## Stop and remove containers, networks, images, and volumes

```bash
$docker-compose down
```
