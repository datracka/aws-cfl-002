- DataBase
- DataWareHouse (for Analytics) - Fast. Infrequently accesed. Store
- Key Value Store. Dumb and fast. data is inconsistent, no relationships, indexes
- Document Database (JSON / XML). Subclases of key values.
	- Tables. Collection of documentes (Array)

## Database services

### NoSQL

**AWS DynamoDB** (Document DB for massive scalability) 
**AWS DocumentDB** (MongoDB)
**AWS Amazon KeySpace** (key / Value) - Apache Casandra

### Relational

Most commonly used type of DB. SQL and Transactions.

RDS. Supports multiple SQL Engines.

- **RDS**
	- Engines
		- **MySQL**
		- **MariaDB**
		- **PostgresSQL**
		- **Oracle**. License
		- **Microsoft SQL Server.** License
	- Offers multi AZ Deployments 
	- Automated backups / snapshots available
- **Aurora**. Fully Managed Database.
	- Fully Managed (Continuous backup, automatic data replication up to  copies your data)
	- Server Less
- **RDS on WMWare.** Allows to have them in on-premise data center

### Other Database Service

- **Redshift**. Data WH (PetaSyze) - Data HOT. For analytics and reports
- **ElasticCache**. Based on Redis or Memcached. for improving performance of application by adding a caching layer.
- **Neptune**. Graph Database
- **AWS TimeStreams.** Event and Time sensitive DB
- **AWS Quantum Ledger Database**. For record of history and financial activities

#### Database Migration Service (DMS)

- on-premise to AWS
- from 2 AWS DB with different engines. (relational)
- from SQL to NoSQL Database
  