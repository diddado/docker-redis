Redis with Redis Commander

You need a ```.env``` file to set the required parameters.  It should look like this:

```bash
COMPOSE_PROJECT_NAME=redis5 # this should be unique for every version of redis since the data volume will be persisted and will be named based on this value.
REDIS_VERSION=5 # the container version you want to use
REDIS_PORT=6379
REDIS_COMMANDER_PORT=8081
```

Run ```docker-compose up``` to start the container.

Browse to http://localhost:8081 to view the database.
