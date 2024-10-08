Requires .env file with next properties filled:

POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres
POSTGRES_DB=mis

additionally for dev profile:

PGADMIN_DEFAULT_EMAIL=admin@admin.admin
PGADMIN_DEFAULT_PASSWORD=admin

`docker compose --profile dev up`

`docker compose --profile production up`