Explain with an example in brief.

1)	Hive Data Definitions
Solution:
-It includes commands that define the different structures in a database.
-HDL is a subset of Hive SQL statements that describe the data structure in Hive by creating, deleting, or altering schema objects such as databases, tables, views.
-The commands are:
CREATE, DROP, TRUNCATE,DESCRIBE,AND ALTER.
Syntax:
CREATE TABLE HIVE_TABLE (abc INT, xyz STRING);       // creating tables
DROP ‘TABLE NAME’; // deleting the table or database
TRUNCATE – used to delete the structure of the table.
ALTER - used to change the structure of the table.

2)	Hive Data Manipulations
Solution:
-It includes commands used to modify the values in the table or to extractthe data from the table.
-The commands are:
LOAD, INSERT, UPDATE, DELETE
-LOAD :- load the data into a table. 
-Update :-change the entries in the table.
3)HiveQL Manipulations
Solution:
HiveQL Manipulations are of three types:
a) Select where 
b)Select order by /sort by 
c) Select group by 
Select where :- used to filter the dataset with the where clause and apply the conditions.
Select order by clause :- used to arrange the dataset in the ascending or descending order by one field or multiple fields.
Select group by :-used to form subsets of the database using different fields of the data.
