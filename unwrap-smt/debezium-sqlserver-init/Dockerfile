FROM mcr.microsoft.com/mssql/server:2017-latest
    ports:
     - 1433:1433
    environment:
     - ACCEPT_EULA=Y
     - MSSQL_PID=Standard
     - SA_PASSWORD=Password!
     - MSSQL_AGENT_ENABLED=true
COPY ./debezium.* /etc/sqlserver/
