# container-watchtower

A Docker Compose container setup for [Watchtower](https://containrrr.dev/watchtower/).

## Table of contents

- [container-watchtower](#container-watchtower)
  - [Table of contents](#table-of-contents)
  - [Setup](#setup)
    - [0. Requirements](#0-requirements)
    - [1. Add environment variables](#1-add-environment-variables)
  - [Usage](#usage)
    - [Start container](#start-container)
    - [Stop container](#stop-container)
  - [License](#license)

## Setup

### 0. Requirements

- Docker
- Docker Compose

### 1. Add environment variables

Add the missing information for the environment variables:

```bash
nano .env
```

Mark the `.env` file so it's not tracked by git:

```bash
git update-index --assume-unchanged .env
```

## Usage

### Start container

```bash
docker compose up -d
````

### Stop container

```bash
docker compose down
```

## License

This project is licensed under the [GNU Lesser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.html) (LGPLv3). You are free to use, modify, and distribute this software under the terms specified in the LGPLv3.

See the [LICENSE](./LICENSE) file for more detailed information.