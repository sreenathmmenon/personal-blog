## Start

## Git Commands

```
git commit -m  "<message>
```
```
git push -u origin master
```
  
```
git push -u origin <branch name>
```
  
### To checkout and create a new Branch

```
git checkout -b <branch name>
```
  
### To see all branches

```
git branch -a
```

Further Reference: https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches


## MongoDB Commands

### View all databases

```
show dbs
show databases
```

Use a database
```
use table1
```

Display data from a table/collection (tables are known as collections)

```
Syntax - db.<collection-name>.find()
db.table.find()
```

### Not master and slave error in MongoDb shell

**Error: error: { "$err" : "not master and slaveOk=false", "code" : 13435 } at src/mongo/shell/query.js:128**

```
rs.slaveOk()
```
Ref: https://stackoverflow.com/questions/17153813/mongodb-replica-set-preventing-queries-to-secondary
