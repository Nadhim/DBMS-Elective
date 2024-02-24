﻿# DBMS-Elective

## Instructions to populate a table using script file

- First set echo on
```sqlplus
sql> set echo on
```
- Copy the path of the file ( Usually Ctrl+Shift+C ) and execute it followed by an @
```sqlplus
sql> @"C:\User\student\Desktop\file.txt"
```

 Execute the above query and the table will be populated.
 In case of any errors, type 'ed' and the edit the query.
 ```sqlplus
sql> ed
```
