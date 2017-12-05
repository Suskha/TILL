# TIL (Today I learned)

#### This is the repo with learned and problem tackled in programming and other stufffs.
 
--------------

--------------

# Nov 13, 2017

#### In the following day I have learned about the linux and it commands available.

Some commands are ls, cd, pwd, mkdir, rm, cp, mv, ln, touch, nano, cat, more, head, tail, top, kill, chmod, ssh, grep, locate, date, uptime, w, whoami, finger, man, whereis, which, tar, gzip, unzip, gunzip, ping, whois, dig, wget, dpkg, diff.


--------------

--------------

# Nov 14, 2017

#### In the following day I have learned about the git (command line) and github.
##### Some commands and remarks
##### 1. To know what files are modified
```bash
$ git status
```

##### 2. To know update files which is to be commited 
```bash
$ git add file_name(for single file)
$ git add -A (all changes)
```

##### 3. To discard changes in working directory 
```bash
$ git checkout -- . file_name
```

##### 4. To commit and commit should always contain message
```bash
$ git commit -m 'message'
```

##### 5. To push into the server
```bash
$ git push origin branch_name
```

##### 6. To pull from the server
```bash
$ git pull origin branch_name
```

##### 7. To specify the username for git
```bash
$ git config --global user.name "user_name"
```

##### 8. To specify the email for git
```bash
$ git config --global email.address "email_address"
```

##### 9. To initialize the git repo
```bash
$ git init
```

##### 10. To specify the username for git
```bash
$ git config --global user.name "user_name"
```

##### 11. To clone git file 
```bash
$ git clone webpageaddress
```

##### 12. Remote
```bash 
$ git remote -v (to view the location of main file and where the file can be push)
$ git remote set-url origin "url" (to set the location of main file and push location)
$ git remote add origin server_name
``` 

##### 13. To view the log
```bash
$ git log
```

##### 14. To branch and to switch to the branches
```bash
$ git branch branch_name (to create the branch)
$ git checkout branch_name (to switch to the branch)
$ git checkout -b branch_name (both at the same time)
```

##### 15. To merge with the master
```bash
$ git merge branch_name
```

##### 16. To view the difference
```bash
$ git diff source_branch target_branch
```

--------------

--------------

# Nov 15, 2017

#### In the following day I have learned about the python.

##### Problem faced :

##### While running the code the module could not be found, module name - "urllib.request"

##### Solution :

##### The problem was due to the version of python. The above module is avaliable in python 3+ but I build the code with python 2+. 

#### New syntax learned 

##### 1. To change string to integer 
```bash
a = int ("10") --- the value of a will be 10 with data type int
```
##### 2. Unpacking argument
```bash
data = [1 ,2 ,3]
sum = 0
def add(*args):
	sum = sum + args
	return sum
	
a = add(*data)

the output will be 6
```

##### 3. Dictionary 
```bash 
data = ['key'='value','key1'='value1']
for k,v in data.items(): #does the loop through all items of dictionary of data and k keeps the key and v keeps the value.
```

##### 4. Sets -- it doesnot allow duplicate.


### Installed conda - anaconda to maintain the environment variable of python

```bash 
$ conda create --name py3 python=3  ------ to create the environment variable of python with version 3+ 
$ conda activate py3 ----- to activate py3 in conda
$ source activate py3 ------ to activate py3 in run time
```
--------------

--------------

# Nov 16, 2017

#### It is the continuation of learning of python

##### 1. try and catch
```bash
try:
	number= input("whats the number")
except:
	pass
finally:
	pass
```
###### Some exception error are ValueError- due to input value error, SyntaxError- due to Typo or syntax error, etc

##### 2. class and def __init__(self): . the __init(self) automatically called after the object of the class is created.

##### 3. Instance variable are unique to each object. Class variable is common to each object.
```bash 
class RRR:
	rrr = 3  # class variable
	def attt(self,x):
		self.ddd = x   # Instance variable
```

##### 4. Multiple inheritance is present class mul(paret1,parent2):

##### 5. Threading : threading is done by importing the threading module
```bash
import threading
class d(threading.Thread):
	def run(self):
		pass

x= d(name="a")
y= d(name="b")

x.start() #to start the threading and calls the run function of class d.
y.start()
```

##### 6. Unpacking of list is possible with unconsistent variable number

##### 7. Zip is used to combine two list

##### 8. lambda is used to create the onetime function.

--------------

--------------

# Nov 17, 2017

#### In the following day I complete the Linear Regression assignment using normal and gradient descent.

--------------

--------------

# Nov 20, 2017

#### In the following day I started learning Core Java Programming.

##### Unknown stuffs of Java.

##### 1. Static variable are called class variables and non-static variables are called instance variable. Non-static method can access static variable but static method cannot access static variable. Static variable or method can only be accessed by class name.

##### 2. final is added to make the variable or method constant.

##### 3. A class can access many interfaces.

##### 4. Anonymous classes can be created as follows
```
Machine mac1 = new Machine() {
	@Override public void start() {
		System.out.println("he");
	}
};
//override the start method of Machine class by creating a child class which is anonymous.
```

##### 5. Also interface can be implemented by creating anonymous class.

##### 6. Read can be performed by Scanner, BufferedReader, FileReader etc and write can be performed by BufferedWriter, FileWriter.

##### 7. Abstract class can be created if the instance of the class is not required but child requires the function of the main class. There can only be one abstract class in the hierarchy.

##### 8. Abstract method forces all child to implements the method but class itself will not be able to use it. It's same as interface.

##### 9. == checks only if two objects are pointing literally at the same two references are pointing literally at the same object. where as .equals() checks if they are equal to each other interms of value.

--------------

--------------

# Nov 21, 2017

#### The following day is the continuation of Core Java course.

##### Unknown stuffs.

##### 10. Like class enum can be created and the object of it can be called.

##### 11. Object can be read or wirte in the file or from the file by serializing and deserializing methods.

##### 12. Arrays of class can be created .
```
Person[] people = {new Person(1,”Sue”),new Person(2,”Mike”)};
```

##### 13. main class can create its own object within it, due to which non-static mehtods can be created and called inside the main mehtod.

##### 14. Types of array i. Arraylist used for fast obtaining data with the help of index. ii. LinkedList used for adding or deleting data from the beginning of the list.

##### 15. Types of map i. HashMap cannot contain duplicate keys and doesnot maintain order. ii. LinkedHashMap maintains the input order. iii. TreeMap arrange in natural order.

##### 16. Types of set are same as maps. i.e. i. HashSet. ii. LinkedHashSet. ii. TreeSet.

Assignment of java started . 

--------------

--------------

# Dec 04, 2017

#### The following day I start MqSql:

Compound key - is the combination of two key to make single unique key but the two key used alone may not be unique.

##### 1. To set mysql user and password 
```bash
$ mysqladmin -u username password "password";
```

##### 2. Show database

	SHOW DATABASES;

##### 3. To select database

	USE databaseName;

##### 4. To view Table inside the database - First select database then 

	SHOW TABLES;

##### 5. To view the structure of the table with name tableName

	SHOW COLUMNS FROM tableName;
	DESCRIBE tableName;

##### 6. To insert data into the table

	INSERT INTO tableName(tableField1 ,tableField2 ....) VALUES('value1','value2'.....);

##### 7. To select data form the table , multiple comparision can be done with where using comparision operators

	SELECT * FROM tableName; # select all data
	SELECT selectField1 .... FROM tableName WHERE user ='particular'; # selects particular users  only
	SELECT selectField1 .... FROM tableName WHERE user IS NULL; # to  check whether the field value is NULL or not

##### 8. To grant permission and flush permission

	GRANT ALL PRIVILEGES ON *.* TO 'userName'@'hostName';
	FLUSH PRIVILEGES;

##### 9. To drop user ,databse,table

	DROP USER 'userName'@'hostName';
	DROP DATABASE databaseName;
	DROP TABLE tableName;

##### 10. To create databases and table

	CREATE DATABASE databaseName;
	CREATE TABLE tableName(tableField tabledatatype , -----);

##### 11. To order the table in ascending order (ASC) descending order (DESC) and LIMIT the output of the query by 1 elemnet

	SELECT * FROM tableName ORDER BY tableField ASC LIMIT 1;

##### 12. Group By is used to group two common data in a field

	SELECT tablefield FROM tableName GROUP BY tableField;

##### 13. Select data from multiple tables

	SELECT table1field,table2field FROM table1,table2 WHERE table1.table1fields = table2.table2fields;

##### 14. Delete data from table

	DELETE FROM tableName WHERE tablefield = something; # deletes according to the comparision
	DELETE FROM tableName; # deletes all data from table

##### 15. Update table

	UPDATE tableName SET tablefield1 = newvalue1 ,tablefield2 = newvalue2 WHERE compariosion;  #  (where optional)


##### 16. Select using LIKE ,REGEXP

	SELECT tablefield FROM tableName WHERE tableField LIKE condition1 [AND | OR ] condition2;
	SELECT tablefield FROM tableName WHERE tableField LIKE '%elp';
	SELECT tablefield FROM tableName WHERE tableField REGEXP '^h';

##### 17. To change the column of table ALTER is used

	ALTER TABLE tableName DROP tableField; # to drop the table field
	ALTER TABLE tableName ADD tableField fieldparameters; # to add table
	ALTER TABLE tableName MODIFY tableField tableparameters; # to modified the field data types or other parameters
	ALTER TABLE tableName RENAME TO newTableName; # to rename the table name
	ALTER TABLE tableName ADD PRIMARY KEY(columnName); # to add primary key
	ALTER TABLE tableNAme ADD INDEX indexName (columnName); # instead of INDEX UNIQUE can be used
	
FIRST can be used to make the table field at starting
AFTER can be used to make the table field after the field table

##### 18. To add index key(creating physical object) but primary key (creating logical object)
	
	CREATE [UNIQUE] INDEX indexName ON tableName(column1,column2,....); # unique is optional

##### 19. create temporary table

	CREATE TEMPORARY TABLE tableName (...........);

temporay table cannot be seen by using show table but we can still add data
deletes after the user is out

##### 20. create clone of a table

	SHOW CREATE TABLE tableName \G; # to view table create table syntax and remame the table name and run the syntax
	INSERT INTO tableNameclone (field names) SELECT FROM * tableName; # to copy every data of tableName to clone table .


##### 21. To make backup to a file
```bash
$ mysql --local-infile=1 -u root -p # to start mysql inorder to write in file
```
	SELECT * FROM tableName INTO OUTFILE 'location';
	SELECT * FROM tableName INTO OUTFILE 'location' FIELDS TERMINATED BY ',' ENCLOSED BY '"' LINES TERMINATED BY '\r\n'; # to make copy of table to local disk
	LOAD DATA LOCAL INFILE 'location' INTO TABLE tableName FIELDS TERMINATED BY ',' ENCLOSED BY '"' LINES TERMINATED BY '\r\n'; # to copy data from local disk to mysql table


##### 22. Make backup using mysqldump
```bash
$ mysqldump -u root -p databaseName tableName > location  # to make copy to table only
$ mysqldump -u root -p databaseName > location # whole database
$ mysql -u root -p databaseName < location # from location to database
```

##### 23. using mysqlimport
```bash
$ mysqlimport -u root -p --local databaseName location
$ mysqlimport -u root -p --local --fields-teminated-by=",", --lines-terminated-by="\r\n" location
```


##### Data types used by my sql

##### 1. INT , size -2147483648 to 2147483647

##### 2. FLOAT(M,D) , M - display length and D - number of decimal points

##### 3. DATE , format YYYY-MM-DD

##### 4. DATETIME , format YYYY-MM-DD HH:MM:SS

##### 5. CHAR(M)  - size 1 -255 character

##### 6. VARCHAR(M) - can define the length of char

##### 7. BLOB or TEXT  - with length of 65535 character


##### Operators and functions available

##### 1. Comparision operators are : < , <= , > , >= , = , != , NULL : IS

##### 2. Logical operators are : AND , OR , NOT

##### 3. YEAR(Date data) - extracts the year from the date field

