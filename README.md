# SQL_Practices

# SQL_Practices
Created a mini healthcare project using SQL scripts like create table, insert, update and stored procedure to perform ETL operation.
## Create table scripts
    1. Created transactional tables for member, provider, claims, facility and healthplan which has transactions of last six months.
    2. Created dimension and fact tables for member, provider, claims, facility and healthplan to save the history of last ten year transactions.
## Create stored procedures
    1. Created a stored procedure which extracts the data from member and transforms the data and loads it to dimension tables.
    2. The latest record in the dimension table is always identified by a field or column called active_flag=1.
    3. Stored procedures are even used to load the fact claim table where it calculates the payer amount and patient amount along with the sarrogate keys of dimension tables.
Scripts are attached in the Git folders.
