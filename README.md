# production_airflow_setup
This repo contain production ready airflow setup.

Install docker, build the dockerfile and run docker-compose.yml. This will spin up airflow api-server and postgres_db containers while it run db migration. You can modify the docker compose to suit your needs.

In the event you can't find a desired provider(s) in the list of Providers, include the provider name in the requirement.txt and rebuild the image i.e dockerfile then restart the docker compose file
