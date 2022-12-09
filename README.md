# Postgres Docker Container

Create a docker container running the latest version of Postgres with a pre populated schema and data.

- Create the schema by adding statements to `./sql/create-schema.sql`
- Populate the schema by adding statements to `./sql/populate-data.sql`

Start the container:

```
$ docker-compose up -d
```

Stop the container
```
$ docker-compose down
```

The database will be available at `localhost:55001`, and the admin username set to `postgres` and the password `postgrespw`.