# container-draw-io

A Docker Compose container setup for [Draw.io](https://github.com/jgraph/drawio)

## Table of contents

- [container-draw-io](#container-draw-io)
  - [Table of contents](#table-of-contents)
  - [Setup](#setup)

## Setup

0. Requirements

   - Docker
   - Docker Compose
   - A running [Traefik instance](https://github.com/jonas-merkle/container-traefik)

1. Add environment variables

    Add the missing information for the environment variables:

    ```bash
    nano .env
    ```
    
    Mark the `.env` file so it's not tracked by git:

    ```bash
    git update-index --assume-unchanged .env
    ```

2. Start container

    ```bash
    docker-compose up -d
    ````

3. Stop container

    ```bash
    docker-compose down
    ```
