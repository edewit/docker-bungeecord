# BungeeCord Container
`Complexity is the enemy of security stability and completion.`
This container is intended to just be a simple BungeeCord server running on the [Docker Java Container with JDK-8 tag](https://hub.docker.com/_/java/). For the sake of sticking to docker standards and application separation this BungeeCord will be the only binary executed in this container. Containers are not intended to have more than one process/service running at a time for security purposes.

You will have to supply your own config.yml

## Invocation

    docker-compose up -d

## Current Status
Incomplete but functional for my needs.

## ToDo
- Add environment variables.

## Health & Statistics
#### Repository Health
[![GitHub issues](https://img.shields.io/github/issues/chamunks/docker-bungeecord.svg?style=flat-square)](https://github.com/chamunks/docker-bungeecord) out of [![GitHub total issues](https://img.shields.io/github/issues-raw/chamunks/docker-bungeecord.svg?style=flat-square)](https://github.com/chamunks/docker-bungeecord)

#### Container Build Health
[![Docker Pulls](https://img.shields.io/docker/pulls/chamunks/docker-bungeecord.svg?style=flat-square)](https://registry.hub.docker.com/u/chamunks/docker-bungeecord/)
[![Docker Stars](https://img.shields.io/docker/stars/chamunks/docker-bungeecord.svg?style=flat-square)](https://registry.hub.docker.com/u/chamunks/docker-bungeecord/)
Status Badge Broken See docker repository page for status.
[![Docker Build Status](http://hubstatus.container42.com/chamunks/docker-bungeecord)](https://registry.hub.docker.com/u/chamunks/docker-bungeecord)

#### Repository Statistics/Info
[![GitHub license](https://img.shields.io/github/license/chamunks/docker-bungeecord.svg?style=flat-square)](https://github.com/chamunks/docker-bungeecord)

[![GitHub forks](https://img.shields.io/github/forks/chamunks/docker-bungeecord.svg?style=flat-square)](https://github.com/chamunks/docker-bungeecord)
[![GitHub stars](https://img.shields.io/github/stars/chamunks/docker-bungeecord.svg?style=flat-square)](https://github.com/chamunks/docker-bungeecord)
