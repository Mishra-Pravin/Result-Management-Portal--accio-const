# Result-Management-Portal--accio-const

The **Result-Management-Portal--Accio-const** is a Java-based Desktop application. 
## Two Features: 


![Main_page](https://github.com/Mishra-Pravin/Result-Management-Portal--accio-const/assets/97659395/984dee02-317f-4b6b-a47c-0ad4ae97f724)

1: Show Result (By entering Student's Roll No.)

2: Add Student (By entering Admin's Login Credential)


## Instructions to run the Project locally
### Setting up MySQL database
1. Create a MySQL database and tables to store the student data and the admin login credentials. The SQL commands used for creating the MySQL database for this project are provided in the SQL file.
2. Add at least one username–password pair for admin credentials in the respective MySQL table to enable administrator login. (This is not specified in the provided _sql_ file.)
### Executing the application
1. Open the project folder in any IDE or code editor such as IntelliJ IDEA, VS Code, Eclipse etc.  
2. Download the ```MySQL Connector``` archive file from [here](https://dev.mysql.com/downloads/connector/j/) and extract it. Install  the ```mysql-connector``` library as a Java library in the project; select the jar file from the extracted folder as the source for the library. 
3. In the java file at the location ```/src/result_portal/DatabaseConnection.java```, add the actual username and password of your MySQL server (as indicated in the comments of the program), so that a connection to the database can be established when the application is executed.  
4. Add the ```rs2xml.jar``` (provided in the ```/dependencies``` folder; or download from [here](https://sourceforge.net/projects/finalangelsanddemons/files/rs2xml.jar/download), for example) as a java library in the project; select the jar file as source for the library.  
5. Run the java file at the location ```/src/result_portal/Index.java```. This file contains the _main_ function that instantiates the application and therefore the project can be executed by running the specified program file.  
6. The application will load in a new window.

### Note:

1. username: ```root```
2. password: ```12345```  

