# Docker Nginx
A Docker container that serves as a PostgreSQL database.

## Run
* Start `docker-compose up --detach`
* Interact `docker exec --tty --interactive pg-docker psql --host=localhost --username=postgres --dbname=postgres`
* Stop `docker-compose down`

## References
* [Don’t install Postgres. Docker pull Postgres - Syed Komail Abbas](https://hackernoon.com/dont-install-postgres-docker-pull-postgres-bee20e200198)