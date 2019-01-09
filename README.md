# elasticsearch

Elasticsearchの自分用Dockerイメージ

## Docker Image

[grandcolline/elasticsearch](https://cloud.docker.com/repository/docker/grandcolline/elasticsearch)

## Plugin

* analysis-kuromoji
* analysis-icu
* repository-s3
* repository-gcs


## Run

```
$ mkdir es_data
$ docker-compose up -d
```

## Build

```
$ docker build -t grandcolline/elasticsearch .
```

