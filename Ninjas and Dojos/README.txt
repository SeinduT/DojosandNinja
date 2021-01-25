Hello

To run this pls create new SCHEMA in MySQL and name it whatever you want. 
(Mine was named just "ninjadojo")

make sure MySQL is running 

open STS and to connect to MySQL

in 
- ninjadojo
	- Src/main/resources
		- application.properties
		change  line 1. last part license to whatever you name the SCHEMA in MySQL 
			line 2. change root to whatever your username is for MySQL
			line 3. change root to whatever your password is for MySQL

right click on app name(ninjadojo)
	- Run As
	- Spring Boot App

in MySQL refresh SCHEMA
	you should see tables created 

Go to localhost:8080 and the app should be up