# Docker Vanilla Minecraft Server

This is based off of [THIS REPO](https://github.com/itzg/docker-minecraft-server)

### Requirements
* docker
* docker-compose

### How to run

```sh
$ docker-compose up -d
```

### How to connect

* On the host running the server: 127.0.0.1:25565
* On another PC in your network: 192.168.0.1:25565 (this could be different)

### FYI

> All the server files will be in minecraft-data
> You can modify server properties but they won't take effect until the server is restarted