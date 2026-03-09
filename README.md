# Dev-Dockerfile-Package-Lab
Lab for Dockerfile Dev Package

## Dev-bot

These instructions are for building and running the dev-bot using the provided dev.py and requirements.txt source files and a user created Dockerfile.

## Prereqs

- Docker installed and running
- A terminal for linux commands like WSL

## How to Build

Run the following command in the directory your project is in

```bash
docker build -t devops-bot .
```

## How to Run

Run the following command once the build command above is finished

```bash
docker run devops-bot
```
