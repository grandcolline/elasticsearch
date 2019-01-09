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
$ docker-compose up -d
```

## Build

```
$ docker build -t grandcolline/elasticsearch .
```

