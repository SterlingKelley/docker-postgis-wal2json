FROM postgis/postgis:12-2.5

# Update the Ubuntu and PostgreSQL repository indexes
RUN apt-get update

# Install wal2json
RUN apt install -y postgresql-12-wal2json postgresql-contrib
