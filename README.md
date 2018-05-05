# H-PHP-Database-Cluster
This small PHP API will enable system to connect with multiples database server (which is running PHP) and sychronize the data between all of the database server. Actually we can achieve this objective via other alternative like using some certain of hardware e.g. Load Balancer or so on.

# My Main Idea
I faced some problem when developing a wide range of data and accessed by small quantity of users but has a very "very" ""very VERY"" big stored data in database and it need clustering a.k.a. sync the data so when an active server goes down, then the system can connect to another server with the same exact query + same exact data.

# The Implementations
As per my first PHP API, `HJS` ("JSON-SQL-STATEMENT, connect a Server PHP to multiple database server"), I will use `HJS` as my main data trasaction method and of course `HJS` uses PDO Database Driver. 
