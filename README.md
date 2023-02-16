# container-draw-io

A Docker Compose container setup for [draw.io](https://github.com/jgraph/drawio)

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

2. Start container

    ```bash
    docker-compose up -d
    ````

3. Stop container

    ```bash
    docker-compose down
    ```
