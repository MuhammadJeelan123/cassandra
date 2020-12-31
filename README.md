# cassandra
Commands for cassandra keyspaces and table /n

#Keyspace
CREATE KEYSPACE SCHOOL
WITH replication = {'class':'SimpleStrategy', 'replication_factor' : 2};

#Table 
Create table employee(empid text primarykey,empname text,designation text,salary double,location text,joined date); 
