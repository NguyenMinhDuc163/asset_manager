﻿# asset_manager
docker-compose down
docker-compose up --build

docker cp db/ddl.sql sqlserver_container:/ddl.sql

sqlcmd -S localhost -U SA -P "password" -d master

sqlcmd -S localhost -U SA -P "password" -d master -i ./db/ddl.sql
