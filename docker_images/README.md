# Airflow Docker Images

## Creating `airflow-data` directory

```sh
mkdir -p ./airflow-data/dags ./airflow-data/logs ./airflow-data/plugins
```

## Running Docker Compose with Celery Executor

```sh
docker-compose -f docker-compose.yaml up --build -d
```

## Running Docker Compose with Celery Executors

```sh
docker-compose -f docker-compose-with-celery-executor-workers.yaml up --build -d
```

## Docker Compose logs

```sh
docker-compose logs
```

## Stop the Running Containers

```sh
docker-compose down --remove-orphans
```

## List the Containers

```sh
docker ps -a
```

## Go inside a Container

```sh
docker exec -it <container-id> /bin/bash
```
