# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY:
``create table student(rollno int,name varchar(10),age int,address varchar(16),phoneno int);``


### OUTPUT:
![image](https://github.com/vidhyasrikachapalayam/F2_DBMS/assets/119477552/7ad3f674-24aa-4ba6-b3c4-7f39807f05ef)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
``alter table student add department varchar(10);``

### OUTPUT:
![image](https://github.com/vidhyasrikachapalayam/F2_DBMS/assets/119477552/401fb920-e013-40f0-b4f6-e865e799a2c8)


### 3) Drop the student table
 
### SQL QUERY: 
`` drop table student;``

### OUTPUT:
![image](https://github.com/vidhyasrikachapalayam/F2_DBMS/assets/119477552/a874af37-2666-4bb1-9b0f-c5daec568cea)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
``TRUNCATE TABLE student;``

### OUTPUT:
![image](https://github.com/vidhyasrikachapalayam/F2_DBMS/assets/119477552/dea0d717-60db-4512-82b8-94f68b393c42)

### 5) Rename the student table to mystudent

### SQL QUERY: 
``alter table student_details rename to mystudent;``

### OUTPUT:

![image](https://github.com/vidhyasrikachapalayam/F2_DBMS/assets/119477552/40122519-3b7c-4ad8-b450-8f7d9d181d1c)

### RESULT:
Thus the ddl command executed successfully.
