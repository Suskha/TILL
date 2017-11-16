# TIL (Today I learned)

#### This is the repo with learned and problem tackled in programming and other stufffs.
 
--------------

--------------

# Nov 13, 2017

In the following day I have learned about the linux and it commands available.
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
	


