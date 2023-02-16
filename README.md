# container-watchtower

A Docker Compose container setup for [Watchtower](https://containrrr.dev/watchtower/).

## Table of contents

- [container-watchtower](#container-watchtower)
  - [Table of contents](#table-of-contents)
  - [Setup](#setup)

## Setup

0. Requirements

   - Docker
   - Docker Compose

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
