# Docker Nginx
A Docker container that serves as a PostgreSQL database.

## Run
* Start `docker-compose up --detach`
* Interact `docker exec --tty --interactive pg-docker psql --host=localhost --username=postgres --dbname=postgres`
* Stop `docker-compose down`