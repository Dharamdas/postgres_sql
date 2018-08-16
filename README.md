# postgres_sql

## Download and setup Postgres SQL DB in local machine for Reference http://www.postgresqltutorial.com/load-postgresql-sample-database/
# Connect to spql command using below command
psql -U postgres
enter DB password
## Post installation download the dvdrental dbsample file and import in Databse using below command
pg_restore -U postgres -d dvdrental Downloads/dvdrental
