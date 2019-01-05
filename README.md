# Docker Postgres Demo: Practical Introduction

## Getting Started with Your Postgres Database

1.) Download [Docker](https://www.docker.com/get-started)

2.) Start your database
```
  docker-compose up
```

3.) Connect to your database

*Connection information needed below*:

  ```
  POSTGRES_USER: "postgres"
  POSTGRES_PASSWORD: "supersecret"
  POSTGRES_DB: "postgres"
  PORT: 5432
  HOST: 127.0.0.1
  ```

## Configuring database
The configuration is happening with the environmental variables set in the **docker-compose.yml** file.  You can edit the file and add additional settings provided by the [Official Postgres Docker image](https://hub.docker.com/_/postgres/).
