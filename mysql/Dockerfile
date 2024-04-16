FROM mysql:latest

RUN mkdir -p /docker-entrypoint-initdb.d

COPY ./sql_scripts /docker-entrypoint-initdb.d/
