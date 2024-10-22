# WIP !!

Requires .env file with next properties filled:


POSTGRES_USER=postgres

POSTGRES_PASSWORD=postgres

POSTGRES_DB=mis

additionally for dev profile:

PGADMIN_DEFAULT_EMAIL=admin@admin.admin

PGADMIN_DEFAULT_PASSWORD=admin

do not forget change permission for pg_admin folder to make it work

`sudo chown -R 5050:5050 ~/mis/pg_admin/`

for better dev experience setup [Poetry](https://python-poetry.org/docs/#installation) first


`docker compose --profile dev up`

`docker compose --profile production up`