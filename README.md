# POC Apache Airflow

This is a POC for Apache Airflow jobs

## How to Run

- clone this repo
- run

`docker compose up`

- once docker container is up and running (both for airflow and postgres)
- go to http://localhost:8080

- in the Airflow UI:

- Go to Admin > Connections
- Choose `postgres_default`
- Edit connection:

(for demo purposes)
````
database: airflow
username: airflow
password: airflow
````