# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:

![271174892-081ff76d-e743-4fee-993b-4fd367716f94](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/739f5db3-7b3c-4846-96d5-a0a60060557b)


### OUTPUT:

![271174912-b667993b-d5b9-4197-be2c-ee7cab1c7d1e](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/784c4dbe-8851-4e32-a274-63eb46ab768b)

### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:

![271174961-c3469723-36d2-4488-ac58-b5c8683a0e93](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/20eaaa8b-48a0-4488-a23d-ce81a68b519f)


### OUTPUT:

![271174985-91233fd3-5dfa-4318-b62f-db528e31914c](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/a4c13682-5608-4993-8a59-a5341754a828)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![271175005-180d48fb-dd02-4d7e-991d-79e92d50f3ae](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/afdf1d9b-148e-4da0-a290-492ae1a8f10e)


### OUTPUT:

![271175026-cbf1e6e9-9633-4cf9-ad85-341e7b03c613](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/efed7d81-55ae-4e67-840f-a42355028b1d)

### Q5)	List the names of Clerks from emp table.


### QUERY:

![271175071-feb4b41d-8428-440b-8961-078212a7e836](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/a4951cd0-020a-46f5-8829-5b3f0d8cb81c)


### OUTPUT:

![271175098-86f71191-94a7-45e6-b756-6020a06350b7](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/cd0df384-27e5-4db2-9b9c-4067d94b2ba9)


### Q6)	List the names of employee who are not Managers.


### QUERY:

![271175146-a65b548c-2cd5-45c9-b21b-89cbdb1114c4](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/9bffe763-35a9-46fb-88c5-ecd6e3966972)


### OUTPUT:

![271175187-02933c79-0073-4274-9b90-2bc9f4814d8b](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/8cfe9290-a5ad-4b16-96a7-4b4d54c501cc)


### Q7)	List the names of employees not eligible for commission.


### QUERY:

![271175220-6d3c980b-752e-4df5-9648-2a4bcf6e1962](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/22123374-3e8e-4613-b5c3-9d6935361600)


### OUTPUT:

![271175271-f4a825b1-ac41-4d65-9b0c-e59a55e4ca33](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/741bd593-34b4-4dde-a333-2a12c12d9042)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:

![271175311-aec361f2-371a-43c0-8be2-7fae5ecfa2e8](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/24b6a336-208d-4ec5-a65e-674e5faa5a0c)


### OUTPUT:

![271175346-6c098d6f-d039-4325-9810-93275772b07f](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/3069cc01-c31d-4457-b6d7-af2843bd8e57)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:

![271175362-89b37e50-40ad-42ab-9d4a-dbba66165238](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/6c4d47be-fe53-4978-9892-b36c765a6d9d)


### OUTPUT:

![271175394-9bd94ed7-a460-4084-8ede-87fdaf6191cf](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/78925f85-389d-4aca-aac8-427431e08fa7)


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:

![271175413-a5349ed1-9a23-4d89-ad1f-4f1ea9cd63c0](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/3d2a96fe-8e6d-41da-aabc-309166707bf3)


### OUTPUT:

![271175439-85269e01-cc98-47d0-8e3a-18ca0b00d42e](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/60ff6adc-0a86-4fed-adbb-9d039ff775bc)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:

![271175474-faf3c43b-22f9-467b-ac0d-ce28c829d279](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/0612ac94-c7db-462b-acb6-26886f26c9a9)


### OUTPUT:

![271175517-4298c229-f964-4b6d-a0a2-a95cf3efb38c](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/04b663c6-2d37-4740-942e-15208676ba27)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:

![271175548-b8bed764-1ff6-4925-a0e7-a6c41359274e](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/ba599927-789f-4925-b4f1-2c302bfe619d)


### OUTPUT:

![271175574-971930f3-b375-4560-acfc-2319350f6264](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/4c3f1017-d785-467f-bb3d-57603d08123a)


### Q13) Find number of rows in the table EMP

### QUERY:

![271175622-ddeee89b-b882-4857-b1b6-9d03bafb1db5](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/0fa76493-688a-493f-baab-9601426d9eb5)


### OUTPUT:

![271175637-d33535ee-03c1-4985-a55c-a101cc7ee17b](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/99e72e54-4e36-427e-9e8e-28413d4fd5f2)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:

![271175678-cf58aa29-f3fa-4c7f-8d1f-d6a59c8ea7dd](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/c5c4b4b5-90b5-4ad6-aa55-397118d8f4d4)


### OUTPUT:

![271175689-4b00eb99-b144-4f53-becb-39f06680a9f3](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/10fe8ee8-527a-445a-9e3d-790ab9f506db)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:

![271175705-534963f4-9772-4bab-90ec-1ccef54fb3c5](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/780ec193-1ae0-4687-800e-0ab9b7be3feb)


### OUTPUT:

![271175721-c0e4cac3-dd5f-40df-84f2-d3126c560d40](https://github.com/prithviraj5703/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121418418/4f568733-e163-4a0b-adf1-7c71ddf82f55)

# RESULT:
To create a manager database and execute DML queries using SQL is executed successfully.
