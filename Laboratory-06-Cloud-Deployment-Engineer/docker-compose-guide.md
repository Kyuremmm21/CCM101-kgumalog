# Docker Compose Guide

## What does the `services` block do?
The `services` block defines all the containers that make up the application. In this file, we defined two services: `database` (MariaDB) and `app` (Nextcloud). Docker Compose uses this block to create, start, and link the containers together.

## How did the Nextcloud app container know how to find the database container?
The Nextcloud container finds the database using the environment variable `MYSQL_HOST=database`. Docker Compose automatically creates a network where containers can communicate using their service names. So the name `database` acts as the hostname of the MariaDB container.

## Difference between `docker run` and `docker-compose up -d`
- `docker run` is used to start **one container at a time**. You have to type long commands and manually link containers.
- `docker-compose up -d` starts **multiple containers** at once using a single YAML file. It is Infrastructure as Code (IaC) — cleaner, repeatable, and easier to manage.
