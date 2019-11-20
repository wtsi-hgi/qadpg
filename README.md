# Quick-and-Dirty PostgreSQL

Get a PostgreSQL database and pgAdmin instance up and running
super-quick, using Docker Compose, with data persisted locally between
runs of the container.

* Start the service:

      ./pg

  Starts a PostgreSQL database instance on port 5432, with a user and
  password of `postgres`; as well as a pgAdmin web console on port 8080,
  with username `pg@example.com` and password `postgres`.

* Stop the service:

      ./pg down

* Start a `psql` session in a running service:

      ./pg sql
