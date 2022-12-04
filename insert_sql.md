insert into emp(empid, fname, lname, desg, qualification, contact) values('100','ABC','A','Engineer','BTech','+00000000')
insert into emp(empid, fname, lname, desg, qualification, contact) values('101','MNO','M','Tech Analyst','BTech','+00000000')
insert into emp(empid, fname, lname, desg, qualification, contact) values('102','PQR','P','Test Engineer','BTech','+00000000')
insert into emp(empid, fname, lname, desg, qualification, contact) values('103','XYZ','X','Seniour Developer','MTech','+00000000')
insert into emp(empid, fname, lname, desg, qualification, contact) values('104','XXX','X','HR','MBA','+00000000')
insert into emp(empid, fname, lname, desg, qualification, contact) values('105','YYY','Y','Junior Eng','MCA','+00000000')


insert into leaves(id, empid, fromdate, todate) values('100','100','1/1/2022','5/1/2022')
insert into leaves(id, empid, fromdate, todate) values('101','100','4/5/2022','6/5/2022')
insert into leaves(id, empid, fromdate, todate) values('102','103','5/10/2022','10/10/2022')
insert into leaves(id, empid, fromdate, todate) values('103','105','2/12/2022','6/12/2022')


insert into loans(id, empid, fname, contact, loan, tenure, emi) values('100','100','ABC','+000000','$5000','5years','100$')
insert into loans(id, empid, fname, contact, loan, tenure, emi) values('101','102','MNO','+000000','$15000','5years','1000$')
insert into loans(id, empid, fname, contact, loan, tenure, emi) values('102','103','PQR','+000000','$50000','5years','500$')
insert into loans(id, empid, fname, contact, loan, tenure, emi) values('103','105','YYY','+000000','$7000','5years','120$')


insert into salary(id, empid, grosssal, netsal) values('100','100','4000','4400');
insert into salary(id, empid, grosssal, netsal) values('101','101','5000$','4600');
insert into salary(id, empid, grosssal, netsal) values('102','102','7000$','7500');
insert into salary(id, empid, grosssal, netsal) values('103','103','9000$','10000');
insert into salary(id, empid, grosssal, netsal) values('104','104','3000$','3800');
insert into salary(id, empid, grosssal, netsal) values('105','105','4000$','4400');
