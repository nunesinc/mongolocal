
## DEV MODE
Run MONGODB on LOCALHOST for development using Docker
## Running the Docker containers
* Tested on  WSL Windows shell

```bash
sudo  docker-compose up -d

```

## How to check MongoDB container is running or not?

```bash
docker ps

```

* Result: 

<IMG SRC= "image-1.png">

## To check our data container, check with command below.

```bash
docker volume ls

```


## MONGODB EXPRESS

Open Brower

```bash
 http://localhost:8081/

```

* Status on Docker Desktop: 

<IMG SRC= "image-2.png">




## Conect a MONGOSHELL

```bash
 docker exec -it mongolocal_mongodb_container_1 mongosh

```