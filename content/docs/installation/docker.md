---
title: Docker
weight: 2
---

You can either use `docker run` or `docker compose`.

## Prerequisites

- Docker
- Docker Compose
- Put your environment vars in `.env` file check [.env.dist](https://github.com/The-MoonTg-project/Moon-Userbot/blob/main/.env.dist) for example format

## `docker run`

We also push images to Docker Hub, so you can use the following commands:

```shell
docker run --env-file ./.env -d qbtaumai/moonuserbot:latest
```

**Updating:**

```shell
docker stop $(docker ps -q)
```

Then re-run the start command.

## `docker compose` [recommended]

### Docker Compose V1 (`docker-compose.yml`)

```shell
# Start
docker-compose -f docker-compose.yml up -d

# Update and run
docker-compose -f docker-compose.yml down && docker-compose -f docker-compose.yml pull && docker-compose -f docker-compose.yml up -d
```

### Docker Compose V2 (`compose.yml`)

```shell
# Start
docker compose -f compose.yml up -d

# Update and run
docker compose -f compose.yml down && docker compose -f compose.yml pull && docker compose -f compose.yml up -d
```

> [!IMPORTANT]
> Make sure you add appropriate env vars
