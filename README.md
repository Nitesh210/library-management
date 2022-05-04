# library-management


Functions
Admin
  Admin account and Login.
  Can Add, View, Book
  
Student
  Can view the book only 
Api of Add, view,delete book
GET http://127.0.0.1:8000/library/?format=json
POST http://127.0.0.1:8000/library/?format=json
example
{
"name":"python"
"isbn":2410
"author":"somesh"
"description":"python book"
}
DEL http://127.0.0.1:8000/library/{id of book to delete}/
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
	
# HOW TO RUN THIS PROJECT
Install Python(3.8.6) (Dont Forget to Tick Add to Path while installing Python)
Open Terminal and Execute Following Commands :
Download This Project Zip Folder and Extract it
Move to project folder in Terminal. Then run following Commands :
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
Now enter following URL in Your Browser Installed On Your Pc
http://127.0.0.1:8000/
	

  
  


