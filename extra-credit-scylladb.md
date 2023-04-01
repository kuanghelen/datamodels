# ScyllaDB
Extra Credit:

ScyllaDB (https://www.scylladb.com/) is an open-source database. 
ScyllaDB is a multi-model database that supports the wide-column store and key-value store. 
It can use the client/server or cloud hosting model. 
Java can access ScyllaDB by using the Scylla Java Driver.

In class, we learned about the multi-model and column data model. 
ScyllaDB utilizes these data models, but its usage of the wide-column model is particularly interesting. 
The wide-column database is a type of columnar database that stores a column family on disk, rather than a single column. 
If the wide-column model is used with appropriate data, this can greatly reduce the number of disk accesses, and therefore reduce the runtime 
(source: https://www.scylladb.com/glossary/wide-column-database/#:~:text=What's%20the%20Difference%20Between%20Columnar,not%20just%20a%20single%20column).
