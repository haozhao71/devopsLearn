## Use Docker Command Run pgadmin
`docker run -d -p 5433:80 --name pgadmin4 -e PGADMIN_DEFAULT_EMAIL=test@123.com -e PGADMIN_DEFAULT_PASSWORD=123456 dpage/pgadmin4`

## Use Docker Command Run Postgres
`docker run -d -p 5432:5432 --name postgres -e POSTGRES_PASSWORD=12345678 postgres:13.4`

## Use Docker Command Run SQL Server
```docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=Zh$12345678" \
   -p 1433:1433 --name sqlserver --hostname sql1 \
   -d mcr.microsoft.com/mssql/server:2019-latest ```
