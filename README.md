## How to run
### Create Database
1. docker volume create petDatabase
2. list: docker volume list
3. look into : docker volume inspect petDatabase
4. docker create --mount source=petDatabase,destination=/var/lib/postgresql/data --name my-postgres -p 5432:5432  -e POSTGRES_PASSWORD=tHLEG_dA1tIMnTt7dl670wp-b6JiVA3n postgres

### Install dependencies
1. npm i

### Run 
1. npm start