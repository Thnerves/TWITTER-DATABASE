# TWITTER-DATABASE
Twitter database where a  it include CRUD operation
CREATE DATABASE DBMSWORKSHOP;
show databases;
use dbmsworkshop;
show tables;
CREATE TABLE Student (Rollno INT NOT NULL PRIMARY KEY, name VARCHAR(100), phonenum INT(10), address VARCHAR(100)); 
show tables;
describe Student;
INSERT into Student (Rollno, name, phonenum, address) VALUES (1,'Harshee',1234567891,'ABC');
INSERT into Student (Rollno, name, phonenum, address) VALUES (2,'Saumya',1987654321,'XYZ');
INSERT into Student (Rollno, name, phonenum, address) VALUES (3,'Sheldon',1029384756,'PQR');
select * from Student;
Alter table Student modify name varchar(50) not null;
describe Student;
Update student set address = 'QWERTY' where rollno = 1;
select * from Student;
delete from Student where rollno = 3;
select * from Student;
TRUNCATE TABLE Student;
select * from Student;
DROP TABLE Student;
select * from Student;
