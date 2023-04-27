
# SQL DATABASE TABLES AND ERD DIAGRAMS


## ERD DIAGRAM 
Entity Relationship Diagram 
type of structural diagram used in database design


bi-directional relationship between two tables 

## Resources
ERD Diagrams
https://online.visual-paradigm.com/

SQL Cheatsheets
https://www.cockroachlabs.com/blog/sql-cheat-sheet/
https://www.datacamp.com/cheat-sheet/sql-basics-cheat-sheet




## Questions

### What is a primary key in SQL

### What's meaning of serial in SQL ===>

### What's another name for rows? Records or Tuples 

### What's another name for Columns? Attributes 

### What is a table? relations of columns and rows 

### What  does the alter keyword do?
change the description of a table

### What is a key? used to link two tables together 

### What is one to one linking?
Connecting two tables, the connection using the foreign key which is a key linking to data columns

### What is one to many? 
When two tables have a relationshiop but a row from one table an have multiple matchin records in another. uses pk-fk relationship.

### What is many to many?
students have many courses and courses have many students.
Multiple records and a third table cojbining both 



## LINKING TABLES 

### One to One 
```
update students 
set student_address_id = 2 where name = "Johhny Bananas"
set student_address_id = 2 where name = "Jackie Lackie"
set student_address_id = 2 where name = "Jilly Cakes"
```


### One-To-Many Relationship 
```
select * from instructors;
INSERT INTO courses 
VALUES (DEFAULT, 'JVA', 'Java Immersive');

INSERT INTO instructors
VALUES (DEFAULT, 'Bobby', 'Bob@sei.net');

UPDATE courses set course_code = 'GIT', course_name = 'Github' where course_id = 4;
```

