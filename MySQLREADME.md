# MySQL Commands 

# MySQL Backup and Restore Commands 

## Taking quick backup of table using folloiwng command
> [!TIP]
> Whenever doing any sensitive operations like update/delete or any operation which can cause datalose always take backup of table.

> [!NOTE] 
> Create New Backup Table  <code> CREATE TABLE newBackUpTableName as SELECT * FROM tableName </code>

## Using mysqldump command 

To check mysqldump is installed 
> mysqldump --version 
