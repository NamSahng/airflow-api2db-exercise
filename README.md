# airflow-api2db-exercise

## Prerequisites
- install docker
- install docker-compose

## Prerequisites for MongoDB
- Make mongodb user
    - https://medium.com/mongoaudit/how-to-enable-authentication-on-mongodb-b9e8a924efac
- Connecting from a Docker container to a local MongoDB
    - https://tsmx.net/docker-local-mongodb/
- Make docker/airflow-pymongo/.env file on like [.env sample](https://github.com/instork/airflow-api2db-exercise/blob/main/docker/airflow-pymongo/.env_example)

## How to run
- run docker-compose
```bash
$ docker-compose up
$ docker-compose up --build --remove-orphans --force-recreate
```

- stop docker-compose
```bash
$ docker-compose down
$ docker-compose down --volumes --remove-orphans
```