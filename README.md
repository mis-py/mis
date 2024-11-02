# Description

This project is designed to provide extendable platform with some useful builtin functionality and good looking web based UI interface.

# Startup

To startup project you need an .env file with next required variables:

`POSTGRES_USER`
`POSTGRES_PASSWORD`
`POSTGRES_DB`
`MONGODB_TABLE`
`MONGODB_INIT_USERNAME`
`MONGODB_INIT_ROOT_PASSWORD`

See `.env.example` for all possible .env variables.

# Dev startup
Dev environment starts without web UI and sever core.
Instead it maps services ports to public so you can connect to them from outside.
Some required variables added in dev .env: 

`PGADMIN_DEFAULT_EMAIL`
`PGADMIN_DEFAULT_PASSWORD`

Also do not forget change permission for pg_admin folder to make it work:

`sudo chown -R 5050:5050 ~/mis/pg_admin/`
