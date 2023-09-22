# spark-docker

Simple Apache Spark standalone cluster using Docker. **Important**: no security features are enabled by default, **do not use this in production environments.**

## Steps

1. Build the Apache Spark base image

```bash
```bash
docker build -t cluster-apache-spark:3.4.1 .
```

2. Start the standalone cluster using Docker compose

```bash
docker compose up
```

