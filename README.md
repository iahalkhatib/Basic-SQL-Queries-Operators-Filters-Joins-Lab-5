![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Joins-Lab-5/assets/170050432/51fa4ae9-2e85-4279-ae8f-7b9839540eed)

# Basic-SQL-Queries-Operators-Filters-Joins-Lab-5


# Task 1. Match employees to their machines

First, I must identify which employees are using which machines. 

The data is located in the machines and employees tables. 

I need to use a SQL inner join to return the records I need based on a connecting column. 

In this scenario, both tables include the device_id column, which I'll use to perform the join. I will run the following query to retrieve all records from the machines table:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Joins-Lab-5/assets/170050432/5ca7af65-53c5-46c5-a586-73fc2805db93)


I'll note that this query is not sufficient to perform the join and retrieve the information I need.

I need to complete the query to perform an inner join between the machines and employees tables on the device_id column.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Joins-Lab-5/assets/170050432/a507f8e6-5557-4b6f-ae15-f7947e7fc566)


# Task 2. Return more data

I now must return the information on all machines and the employees who have machines. 

Next, I must do the reverse and retrieve the information of all employees and any machines that are assigned to them. 

To achieve this, I'll complete a left join and a right join on the employees and machines tables. 

The results will include all records from one or the other table. 

I must link these tables using the common device_id column. 

I will run the following SQL query to connect the machines and employees tables through a left join.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Joins-Lab-5/assets/170050432/09549906-34a0-4514-a17c-dfe4d6cda601)


I will run the following SQL query to connect the machines and employees tables through a right join.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Joins-Lab-5/assets/170050432/bfcaad40-3c44-4161-9d1d-7c68168da025)


# Task 3. Retrieve login attempt data


To continue investigating the security incident, I must retrieve the information on all employees who have made login attempts. 

To achieve this, I'll perform an inner join on the employees and log_in_attempts tables, linking them on the common username column.

I will run the following SQL query to perform an inner join on the employees and log_in_attempts tables.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Joins-Lab-5/assets/170050432/31d73a30-a519-4e0d-9f2d-80a6d1478968)


# I now have practical experience in using INNER JOIN, LEFT JOIN, and RIGHT JOIN.
