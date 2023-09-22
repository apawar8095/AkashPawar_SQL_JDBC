#AkashPawar_SQL_JDBC/tree/main/JDBC_graded_assignment

in backend 
created new db
tn
created table using below query

CREATE TABLE employee (
    Id INT PRIMARY KEY,
    Name VARCHAR(10) NOT NULL,
    Email_Id VARCHAR(30) NOT NULL,
    Phone_Number VARCHAR(15)
);


please make sure that before running project create table employee in your machine

Modify Email_Id column to varchar(30) NOT NULL.

ALTER TABLE employee
MODIFY Email_Id VARCHAR(30) NOT NULL;
