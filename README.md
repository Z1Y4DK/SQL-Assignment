# <v></v> <div align="center"> Hi Welcome to my SQL Assignment: 👋  <div/> 
<p> 

## <div align="left">  **Content:**
**Importing Dataset and running** <p>
**Querying Tasks** <p>
**Answering Questions** <p>
**Documentation**

## <v></v> <div align="left"> Impoting Dataset: <div/> 
To import a dataset into a SQL database, you can use SQL's built-in tools such as LOAD DATA INFILE in MySQL or COPY in PostgreSQL to directly import CSV or text files. Alternatively, I could have used SQL client tools with import functionalities, programming languages like Python to write scripts for data insertion for more complex tasks.

## <v></v> <div align="left"> Querying Tasks: <div/> 
To query tasks in SQL, I used the SELECT statement followed by the columns I want to retrieve, specifying the table name with FROM. For instance, SELECT * FROM tasks; fetches all tasks from a table named "tasks". To filter results, I use the WHERE clause, like SELECT * FROM tasks WHERE status = 'completed'; to fetch completed tasks.
Most common statements are:

**SELECT:** Retrieves data from a database table. It allows you to specify which columns you want to retrieve and filter the results based on specified conditions using the WHERE clause.

**INSERT:** Adds new records into a database table. It allows you to specify the values for each column in the new record.

**UPDATE:** Modifies existing records in a database table. It allows you to change the values of specific columns in existing records based on specified conditions using the WHERE clause.

**DELETE:** Removes records from a database table. It allows you to specify conditions to filter the records that should be deleted using the WHERE clause.

**CREATE:** Creates a new database, table, index, or other database objects. It allows you to define the structure and properties of the object being created.

**ALTER:** Modifies the structure of an existing database object, such as adding or dropping columns from a table, modifying column data types, or renaming objects.

**DROP:** Deletes an existing database object, such as a table, index, or view, from the database.

**TRUNCATE:** Removes all records from a table, but keeps the table structure intact. It is faster than DELETE as it doesn't generate individual delete operations for each record.

**GRANT:** Gives specific privileges or permissions to users or roles on database objects.

**REVOKE:** Removes specific privileges or permissions previously granted to users or roles on database objects.
## <v></v> <div align="left"> Answering Questions: <div/> 
We are then given a list of questions in order to answer from the dataset. We pull data using the SQL statements to get the answer to the questions which are:

## <v></v> <div align="left"> Documentation: <div/> 
