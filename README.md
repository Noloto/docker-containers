# WIP: Useful Docker Containers

## Usage

To run a container on your local machine - within your Terminal navigate to the folder of the specific _application/version_ and run:

```
docker-compose up -d
```

## Environment

| Database   | Username    | Password    |
| :--------- | :---------- | :---------- |
| MongoDB    | development | development |
| MariaDB    | development | development |
| Pocketbase | -           | -           |
| Redis      | -           | -           |

# Pocketbase

Pocketbase is a easy to use, fast to setup Open source backend contained in one file

It provides you with a UI Admin dashboard to create your Database collections and insert data. Pocketbase delivers a ready to use API endpoint for each database collection you create.

Furthermore you can perform requests, with all your favorite Frontend Frameworks, on the API with the [pocketbase npm package](https://www.npmjs.com/package/pocketbase).
