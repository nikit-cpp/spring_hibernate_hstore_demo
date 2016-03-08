Postgres Key-Value
==================
https://github.com/jamesward/spring_hibernate_hstore_demo
sudo dnf install postgresql-contrib
createdb ps_kv
psql -U nik -h localhost ps_kv
create extension hstore;
\q


PORT	8081
DATABASE_URL	jdbc:postgresql://localhost:5432/ps_kv
DATABASE_USER	nik
DATABASE_PASSWORD	password