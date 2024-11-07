# POC Project - Local Rancher

This is a simple proof of concept (POC) project to run Rancher on a local machine using Docker Compose.

## Prerequisites

- Docker installed on the local machine
- Docker Compose installed on the local machine

## Setup

#### Clone this repository:

```sh
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

## Running Rancher

1. Start the services defined in `docker-compose.yml`:

```sh
docker-compose up -d
```

2. Access Rancher in your browser:

- [http://localhost](http://localhost)
- [https://localhost](https://localhost)

## Stopping the Services

To stop the services, run:

```sh
docker-compose down
```


## Cleanup
To remove all containers, volumes, and networks created by Docker Compose, run:
```sh
docker-compose down -v
```
