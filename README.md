# Development Databases using docker

Installing Databases into your local systems can be a pain sometimes. Keeping that in mind I have created a list of databases here which are most commonly used on daily projects.

## Steps

1. Install [Docker Engine](https://docs.docker.com/engine/install/) and [Docker Compose](https://docs.docker.com/compose/install/).
2. Navigate to the particular folder and run *docker-compose up -d*

Simple as that<b>!</b>

The databases supported are:

1. Dynamodb
2. ElasticSearch
3. MongoDb
4. MySQL
5. PostgreSQL
6. Neo4j



The dockers are configured in such a manner that it will persist data in your local machine in a folder named ```<database>-data```.

The password is ```example``` whereever applicable.