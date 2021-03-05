# Bookinfo Rating Service

Rating service has been developed on NodeJS


## How to run with Docker

```bash
# Build Docker Image for rating service
docker build -t bookinfo .

# Run MongoDB with initial data in database
docker run -it -p 8080:8080 bookinfo


```

* Test with path `/datails/1` and `/health`


## How to run with Docker Compose 
```bash
docker-compose up
```