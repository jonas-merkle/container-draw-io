# container-draw-io

docker compose container setup for [draw.io](https://github.com/jgraph/drawio)

## setup

0. requirements

   - docker
   - docker-compose
   - a running [traefik instance](https://github.com/jonas-merkle/container-traefik)

1. add environment variables

    ```bash
    nano .env
    ```

    add the missing information for the environment variables

2. start container

    ```bash
    docker-compose up -d
    ````

3. stop container

    ```bash
    docker-compose down
    ```
