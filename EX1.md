# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## DATE:8.8.23
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
```
create table student(
  2    rollno char(5),
  3    name varchar(20),
  4    age char(5),
  5    address varchar(100),
  6    phoneno char(30));

```
### OUTPUT:
![image](https://github.com/RKavikeerthana/F2_DBMS/assets/120431120/b4f59913-32e1-4d7a-a015-41f702f63ce7)



### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
 ALTER TABLE student
 ADD department varchar(15);
```
### OUTPUT:
![image](https://github.com/RKavikeerthana/F2_DBMS/assets/120431120/0cdccb8f-16f8-4388-bdc3-dae681e29ba5)



### 3) Drop the student table
 
### SQL QUERY: 
```
 drop table student;
```
### OUTPUT:
![image](https://github.com/RKavikeerthana/F2_DBMS/assets/120431120/ca33c63f-42e8-49a0-b8cf-234a97dc54b1)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
 truncate table student;
```
### OUTPUT:
![image](https://github.com/RKavikeerthana/F2_DBMS/assets/120431120/ce1ef582-cf0e-4938-80e2-db0015a82894)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```
 alter table student
 rename to mystudent;
```
### OUTPUT:
![image](https://github.com/RKavikeerthana/F2_DBMS/assets/120431120/e4e7a7f7-40c1-425b-a332-ca3fb8fe79a2)

### RESULT:
Hence successfully created a student database and execute DDL queries using SQL.
