# Contacts APP
This is a simple contacts web app that uses htmx and go templates 


## Setup

You can run the docker-compose file located in docker/ directory
```(bash)
cd docker/
docker compose up -d
```

## Services

The compose provides 3 Services

- postgres as the db(storage is ephemeral in docker remember unless stated differently)

- adminer as the gui to interact with the psql database 
- contacts as the web server that hosts the contacts app 
