# library-management


Functions
Admin
  Admin account and Login.
  Can Add, View, Book
Student
  Can view the book only 
	
# Prerequisites
## MySQL
Install MySQL
Install MySQL Workbench
Create an empty schema named book in MySQL
Import /source/test.sql file into book schema via
Replace USERNAME with the your local instance MySQL username, which is usually root
Replace PATH with the actual path of /source/test.sql file
Input the password for your local instance MySQL afterwards
mysql -u USERNAME -p test < PATH
In book schema, the following tables are important:
auth_user stores all the users including readers, staff and superusers
books stores the book info
libraries stores the library info
loans stores the loan info
reserves stores the reservations
comments stores the comments
storages stores the storage info
	
	

  
  


