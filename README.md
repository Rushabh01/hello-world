# hello-world
First repository

MySQL program to create a table and display table:

create database fycs13;
show databases
use database fycs13;
create table employee(eid int primary key,ename varchar(15),deptno int,salary int);
insert into employee values(100,"Abc",30,7000);
insert into employee values(200,"Def",10,8000);
insert into employee values(300,"Pqr",20,6000);
insert into employee values(400,"Xyz",50,9000);
insert into employee values(500,"Mno",50,9000);
select * from employee;
