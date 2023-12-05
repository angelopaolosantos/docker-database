# Run Databases on Docker

Create a MySQL and a Postgres Database Containers
Create an Adminer Container

### Run docker compose
```
docker-compose -f ./docker-compose.yml up -d
```

### Clean up
```
docker-compose -f ./docker-compose.yml down -v --rmi all
```