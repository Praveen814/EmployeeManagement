Emp Table
|Field        |Type        |Null|Key|Default|Extra|
|-------------|------------|----|---|-------|-----|
|empid        |int         |NO  |PRI|null   |     |
|fname        |varchar(100)|YES |   |null   |     |
|lname        |varchar(100)|YES |   |null   |     |
|desg         |varchar(100)|YES |   |null   |     |
|qualification|varchar(100)|YES |   |null   |     |
|contact      |varchar(100)|YES |   |null   |     |

---------------------------------------------------
Leaves Table
|Field        |Type        |Null|Key|Default|Extra|
|-------------|------------|----|---|-------|-----|
|id           |int         |NO  |PRI|null   |     |
|empid        |int         |YES |   |null   |     |
|fromdate     |date        |YES |   |null   |     |
|todate       |date        |YES |   |null   |     |

---------------------------------------------------
Loans Table
|Field        |Type        |Null|Key|Default|Extra|
|-------------|------------|----|---|-------|-----|
|id           |int         |NO  |PRI|null   |     |
|empid        |int         |YES |   |null   |     |
|fname        |varchar(100)|YES |   |null   |     |
|contact      |varchar(100)|YES |   |null   |     |
|loan         |varchar(100)|YES |   |null   |     |
|tenure       |varchar(100)|YES |   |null   |     |
|emi          |varchar(100)|YES |   |null   |     |

---------------------------------------------------
Salary Table
|Field        |Type        |Null|Key|Default|Extra|
|-------------|------------|----|---|-------|-----|
|id           |int         |NO  |PRI|null   |     |
|empid        |int         |YES |   |null   |     |
|grosssal     |varchar(100)|YES |   |null   |     |
|netsal       |varchar(100)|YES |   |null   |     |
