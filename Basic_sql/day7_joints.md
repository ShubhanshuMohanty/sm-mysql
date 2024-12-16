 ### 1. Table Creation and Data Insertion

 ```sql
 create table employee
     (
              eid int,
              ename varchar(23),
            did int
     );
 create table department
     (
              did int primary key,
              department varchar(23)
     );
```

### inserting data

```sql
insert into department values(1,"IT");

insert into department values(2,"HR");

insert into department values(3,"Accounts");

insert into department values(4,"Admin");

insert into department values(5,"finance");

insert into employee values(11,"Ran",2);

insert into employee values(12,"shyam",1);

insert into employee values(13,"ghanshyam",1);

insert into employee values(14,"Radheshyam",4);

insert into employee values(15,"Ranshyam",5);
```

 
