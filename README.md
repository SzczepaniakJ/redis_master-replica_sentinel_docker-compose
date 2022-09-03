# Redis Master 2 Slaves/Replicas with 3 Sentinels

## Quickstart (Ubuntu)

1. Create docker network
    ```console
    docker network create --driver bridge --subnet 172.19.0.1/24 redis_net
    ```
2. Run docker-compose
    ```console
    docker-compose up -d
    ```
3. Check if everything is running
    ```console
    docker network inspect redis_net
    ```
    ```console
    docker ps
    ```