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

# Dec 04, 2017 - Dec 06,2017

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

##### 9. To drop user ,database,table

	DROP USER 'userName'@'hostName';
	DROP DATABASE databaseName;
	DROP TABLE tableName;

##### 10. To create databases and table

	CREATE DATABASE databaseName;
	CREATE TABLE tableName(tableField tabledatatype , -----);

##### 11. To order the table in ascending order (ASC) descending order (DESC) and LIMIT the output of the query by 1 elemnet

	SELECT * FROM tableName ORDER BY tableField1,tableField2 ASC LIMIT 1;
	SELECT * FROM tableName LIMIT startNumber,numberOfData;

##### 12. Group By is used to group two common data in a field and uing HAVING

	SELECT tablefield FROM tableName GROUP BY tableField;
	SELECT tablefield FROM tableName GROUP BY tableField HAVING tableField = '';

##### 13. Select data from multiple tables

	SELECT table1field,table2field FROM table1,table2 WHERE table1.table1fields = table2.table2fields;
	SELECT tableName.tableField FROM tableName;

##### 14. Delete data from table

	DELETE FROM tableName WHERE tablefield = something; # deletes according to the comparision
	DELETE FROM tableName; # deletes all data from table

##### 15. Update table

	UPDATE tableName SET tablefield1 = newvalue1 ,tablefield2 = newvalue2 WHERE compariosion;  #  (where optional)


##### 16. Select using LIKE ,REGEXP ,BETWEEN ,IN

	SELECT tablefield FROM tableName WHERE tableField LIKE condition1 [AND | OR ] condition2;
	SELECT tablefield FROM tableName WHERE tableField LIKE '%elp'; # % for all and _ for single
	SELECT tablefield FROM tableName WHERE tableField REGEXP '^h';
	SELECT tablefield FROM tableName WHERE tableField BETWEEN value1 AND value2;
	SELECT tablefield FROM tableName WHERE tableField IN ("data",......); # works same as many or
	SELECT tablefield FROM tableName WHERE tableField NOT IN ("data",......);

##### 17. To change the column of table ALTER is used

	ALTER TABLE tableName DROP [COLUMN] tableField; # to drop the table field
	ALTER TABLE tableName ADD tableField fieldparameters; # to add tablefield
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
$ mysql -u root -p databaseName '<' Llocation # from location to database
```

##### 23. using mysqlimport
```bash
$ mysqlimport -u root -p --local databaseName location
$ mysqlimport -u root -p --local --fields-teminated-by=",", --lines-terminated-by="\r\n" location
```

##### 24. To get distinct data from similar data

	SELECT DISTINCT * FROM tableName;
	
##### 25. To create custom column with its own structure

	SELECT CONCAT(tablefield, ', ',tablefield) FROM tableName; # to view only
	SELECT CONCAT(tablefield, ', ',tablefield) AS newTableFieldName FROM tableName; # giving name to new concated data
	SELECT tablefield1,tablefield1-1 AS newName FROM tableName;

##### 26. Subqueries

	SELECT tableField FROM tableName WHERE tableField > (
	SELECT tableField FROM tableName  --it is done first 
	) ORDER BY tableField;

##### 27. JOIN

left outer join

	SELECT tablename1.tablefield , tablename2.tablefiled FROM tablename1 LEFT OUTER JOIN tablename2 ON tablename1.tablefield = tablename2.tablefield;
	--selects all value from left table i.e tablename1
	
right outer join

	SELECT tablename1.tablefield , tablename2.tablefiled FROM tablename1 RIGHT OUTER JOIN tablename2 ON tablename1.tablefield = tablename2.tablefield;
	 --selects all value from right table i.e tablename2
	 
##### 28. UNION

	SELECT tablefield1,tablefield2 FROM tablename WHERE tablefield3 > something
	UNION
	SELECT tablefield1,tablefield2 FROM tablename WHERE tablefield4 > something;
	-- UNION removes duplicate entry and UNION ALL keeps duplicate entry
	
##### 29. fulltext searching

	ALTER TABLE tableField ADD FULLTEXT(tablefield); 
	-- to enable fulltext in tablefield
	SELECT tablefield FROM tableName WHERE Match(tableField) Against('search item');
	-- tableField should be fulltext enabled
	SELECT tablefield FROM tableName WHERE Match(tableField) Against('+search item -notincluded item' IN BOOLEAN MODE);

##### 30. To create view

	CREATE VIEW viewName AS SELECT filedNmae FROM tableName
	ORDER BY fieldName;

##### Data types used by my sql

 1. INT , size -2147483648 to 2147483647
 2. FLOAT(M,D) , M - display length and D - number of decimal points
 3. DATE , format YYYY-MM-DD
 4. DATETIME , format YYYY-MM-DD HH:MM:SS
 5. CHAR(M)  - size 1 -255 character
 6. VARCHAR(M) - can define the length of char
 7. BLOB or TEXT  - with length of 65535 character

##### Operators and functions available

 1. Comparision operators are : < , <= , > , >= , = , != , NULL : IS
 2. Logical operators are : AND , OR , NOT
 3. YEAR(Date data) - extracts the year from the date field
 4. CONCAT(fields) - adds to value
 5. UPPER(filed) - creates string with all uppercase
 6. SQRT(field) - square roo the filed data
 7. AVG(field) - gives the average of the field
 8. SUM(field) - adds all the data of the field
 9. COUNT(field) - counts the how many time the data is repeated
 10. MAX(field) - gives maximum value
 11. MIN(field) - gives minimum value
 12. AS can be used to give nick name to table field,table,


--------------

--------------

# Dec 08, 2017

#### The following day I started Mongodb:

To start mongodb by terminal : 
```bash
$ sudo service mongodb start
$ sudo mongo
$ sudo service mongodb stop
```

##### Syntax of mongodb

- To **show databases** : 
	
		show dbs
	
- To create **new database**:

		use databasename;
		
- To delete **database**

		db.dropDatabase();

- To know the currently **working databse**:

		db

- To create **user**:

		db.createUser(
		{user= "grunze",
		pwd="changeme",
		roles=["readWrite","dbAdmin"]
		});
    
- To create **Collections** and **view** the collection in the database:

		db.createCollections('collectionName'); --to create collections
		-- collection can also be created by directly inserting data
		
		show collections --to show collection
		
- To **drop collections** :

		db.collectionName.drop();

- To **insert data** in **collections** :

		db.collectionName.insert([{
		fieldName:"grunze",
		fieldName:123},
		{for more data}
		]);
		
		db.collectionName.find();  --to view collection data
		
- To **update** the data:

		db.collectionName.update(
		{fieldName:"toFind"},
		{fieldName:"toUpdateto with other non updating field"}
		);
		
	- to find and add particular value:
	
			db.collectionName.update(
			{fieldName:"toFind"},
			{$set:{fieldName:"toUpdateto"}}
			);
		
	- to check and update data, if not present then add :

			db.collectionName.update(
			{fieldName:"toFind"},
			{fieldName:"toUpdateto with other non updating field"},
			{upsert : true}
			);
			
	- to update multiple data at once
	
			db.collectionName.update(
			{fieldName:"toFind"},
			{$set:{fieldName:"toUpdateto"}},
			{multi:true}
			);			

- To **increment value** :

		db.collectionName.update(
		{fieldName:"toFind"},
		{$inc:{fieldNameToIncrement:byHowmuch}}
		);
		
- To **remove** a **field**:

		db.collectionName.update(
		{fieldName:"toFind"},
		{$unset:{fieldNameToRemove:1}}
		);
		
		
- To **rename** field:
	
		db.collectionName.update(
		{fieldName:"toFind"},
		{$rename:{oldfieldName:newFieldName}}
		);
		
- To **remove data** :

	- To remove all data with common fieldName:
	
			db.collectionName.remove(
			{fieldName:"toRemove"}
			);
	
	- To remove only first data it finds
	
			db.collectionName.remove(
			{fieldName:"toRemove"},
			{justOne:1}
			);
		
- To **find data**:

		db.collectionName.find();

	- normal find:
	
			db.collectionName.find(
			{fieldName:"toFind"});
			
	- find only one:
	
			db.collectionName.findOne();
			
	- by using **or**:
	
			db.collectionName.find(
			{$or:[
			{fieldName:"tofind"},
			{fieldName:"tofind"}]});
			
	- by using **lt**(less than) or **gt**(greater than) or **lte**(lt or equals to ) or **gte**(gt or equals to) or **ne**(not equal to):
	
			db.collectionName.find(
			{fieldName:{$lt:value}}
			);
	
	- in object:
	
			db.collectionName.find(
			{"fieldName.fieldNameVariable":"fieldvalue"});
			
	- To select field as required:
	
			db.collectionName.find({},{
			fieldName:1,_id:0});
			
- To sort data:

		db.collectionName.find().sort(
		{fieldName:order});
		--order for asc = 1 , desc = -1
		
- To count :

		db.collectionName.find().count();
		
- To limit :

		db.collectionName.find().limit(value);
		
- use of foreach :

		db.collectionName.find().forEach(function(doc){print("A: " +doc.fieldName)});
		
- To skip :
		
		db.collectionName.find().skip(value);
		
- To create, get and drop **index** :

		db.collectionName.ensureIndex({fieldName:1});
		
		db.collectionName.getIndexes();
		
		db.collectionName.dropIndex({indexedFieldName:1});
		
- Aggregation

		db.employees.aggregate([{$group:{_id:"$fieldName",total:{$sum:1}}}]);
		
		db.employees.aggregate([{$group:{_id:"$fieldName",MaxAge:{$max:"$Age"}}}]);
		
- Backupp and restore
	
		mongodump;
		
		mongorestore;
		
		mongodump --db databaseName
		
		mongorestore --db databaseName path
		
		mongodump --db databaseName --collection collectionName
		
		mongorestore --db databaseName --collection collectionName path
		
		
--------------

--------------

# Dec 11, 2017

#### The following day I started Advanced Java:

- Some deciding condition:
	
	- Is a (decides if class should extends another class)
	
			Is a 'Dog' an 'animal' - true (Dog extends animal)
			Is a 'Dog' a 'cat' - false (Dog doesnot extends animal)
	
	- Has a (decides if something is a field)
	
			'Dog' has a 'height' - true (dog requires a height field)
			
- decoupling 

- Observer pattern - loose coupling

- to get negative random number in java

		(Math.random()*(.06))-.03;
		

***
***


# Dec 22,2017

#### The following day I stated Gradle:

* Gradle uses Groovy domain specific language.

* To be a gradle project the project should contain 'gradle.build' file.

* How to view task in gradle:

```bash
$ gradle tasks
```

* How to run gradle project: 

```bash
$ gradle build
```
It creates the build folder in the main directory.

* apply plugin : "java" -- for every java project and adds few task to project.

* sourceSets -- represents a logical group of Java source and resources.
		
	* one way to write sourceSets.
	
			sourceSets {
				main.java.srcDir "src/main"
				test.java.srcDir "src/main"
			}
		
	* second way to write sourceSets.
	
			sourceSets.main.java.srcDir "src/main"
			
	* third way to write sourceSets.
	
			sourceSets {
				main {
					java {
						// srcDir "src/main"
						// srcDir("src/main")
						srcDir = ["src/main"]
					}
				}
			}
	
* Manifest file should contain :
		
		Main-Class : ___.___.__.Main
		
* To write the required path in the Manifest file during the gradle build :

		jar {
			manifest.attributes "Main-Class": "____.___.__.Main"
		}
		
* To add dependencies :
	* location of dependencies is defined by following ways :
		
			repositories {
				// maven { url "urlNmae" }
				mavenCentral()
			}

	* which dependencies is required is defined by following method :
		
			dependencies {
				compile "groupID:artifactID:version"
				compile group:"groupID", name: "artifactID",version:"version"
			}

	* To add the dependencies in the required folder for jar file :
	
			jar {
				from configurations.compile
				// adds jar file  directly to the jar file of the program
				from configurations.compile.collect { entry -> zipTree entry }
				from configurations.compile.collect { zipTree it }
			}
			
	* To add configuration :
		
			configurations {
				myConfig
			}
			
			dependencies {
				myConfig "groupID:artifactID:version"
			}
			
			jar {
				from configurations.myConfig.collect { zipTree it }
			}

	* Artifacts
		
			artifacts {
				myconfig jar
			}

* To view the dependencies
```bash
$ gradle dependencies
```

* To create custom task :

		task taskName(group: 'greeting', description: 'Greets you.')
		task taskName {
			group 'greeting'
			description 'Greets you'
			
			// during configuration phase
			println 'hello'
			ext.greeting = 'Hey' 
			
			// during execution phase
			doLast { println 'second!' }
			doLast { println 'third' }
			doFirst { println 'first' }
			doLast { println "Greeting: $greeting" }
			
		}

		hello << { println 'I was appended using <<' }    ---- same as doLast
		
		
		task runJar(type: Exec, dependsOn: jar) {
			exectuable 'jar'
			args '-jar', "$jar.archivePath", 'HelloWorld'
		}
		
		task run(type: JavaExec, dependsOn: classes) {
			main '----.---.---.Main'
			classpath sourceSets.main.runtimeClasspath
			args 'Hello World'
			args '-jar
		}
		
		task hello {
			onlyIf { true }
		} << {
			println 'Hello!'
		}
		
		hello enabled = false

***
***

#




































