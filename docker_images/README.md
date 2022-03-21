# Airflow Docker Images

## Creating airflow-data directory

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

## Stop the running container

```sh
docker-compose down --remove-orphans
```