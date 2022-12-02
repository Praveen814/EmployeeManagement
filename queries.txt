emp table:
----------
create table emp(empid int PRIMARY key, fname varchar(100), lname varchar(100), desg varchar(100), qualification varchar(100), contact varchar(100));

salary table:
-------------

create table salary(id int PRIMARY KEY, empid int, grosssal varchar(100), netsal varchar(100));


leaves table:
-----------------

create table leaves(id int primary key, empid int, frodate date, todate date);

loans table:
------------

create table loans(id int primary key, empid int, fname varchar(100), contact varchar(100), loan varchar(100), tenure varchar(100), emi varchar(100));





