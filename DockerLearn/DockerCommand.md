## Use Docker Command Run pgadmin
`docker run -d -p 5433:80 --name pgadmin4 -e PGADMIN_DEFAULT_EMAIL=test@123.com -e PGADMIN_DEFAULT_PASSWORD=123456 dpage/pgadmin4`

## Use Docker Command Run Postgres
`docker run -d -p 5432:5432 --name postgres -e POSTGRES_PASSWORD=12345678 postgres:13.4`
