# MY-1ST-DOCUMENTATION
MY JOURNET WITH DSA AS A STUDENT LEARNING DATA ANALYSIS (PORTFOLIO BUILDING)
I have learnt many things, ranging from Ms Excel, SQL and how to buld a portfolio
## project topic: Northwest sales analysis 

project overview
create database DSA_DB


---------------create table -------------------
create table Employee(
Staffid varchar (10),
FirstName varchar (100),
LastName Varchar (100),
Gender nvarchar (10),
Date_of_Birth date,
HireDate date
primary key (staffid)
);


insert into Employee (staffid, firstname, LastName, gender, DateoFBirth,hiredate)
values ( 'AB201', 'Ayan', 'Olakun', 'female', '1992-08-22', '2018-02-09'),
( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09'),
( 'AB223', 'joshua', 'chukwuemeka', 'male','1980-10-09', '2022-02-09'),
( 'AB234', 'sanni', 'ibrahim', 'male','1958-10-09', '2019-09-23'),
( 'AB254', 'mercy', 'olanipekun', 'female','1982-10-09', '2020-02-09'),
( 'AB249', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB298', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB260', 'deborah', 'justin', 'female','1982-10-09', '1988-02-09'),
( 'AB281', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09')

SELECT * FROM EMPLOYEE

drop table employee
