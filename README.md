# Quick-and-Dirty PostgreSQL

Get a PostgreSQL database instance and pgAdmin web console up and
running super-quick, using Docker Compose, with data persisted locally
between runs of the container.

* Start the service:

      ./pg

  Starts a PostgreSQL database instance on port 5432, with a user and
  password of `postgres`; as well as a pgAdmin web console on port 8080.

* Stop the service:

      ./pg stop

* Start a `psql` session in a running service:

      ./pg sql
