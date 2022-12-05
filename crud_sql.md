**CREATE**
create table customers (
	custnumber int ,
	firstname varchar(30),
	lastname varchar(20),
	phone varchar(10),
	address varchar(30),
	primary key(custnumber)
);

insert into customers values
(100,'Adam','Wane','1234567890','XYZ'),
(101,'Samy','Sid','0986543211','ABC');

**READ**
select netsal from emp, salary where emp.empid = salary.empid and emp.empid='102';

select * from customers;

**Update**
update customers
set phone='1230984568'
where custnumber=101;

**DELETE**
Delete from customers where custnumber=100;

delete from Emp where empid=102;
