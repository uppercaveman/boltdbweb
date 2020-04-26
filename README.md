# boltdbweb
A simple web based boltdb GUI Admin panel.


##### Installation
```
go get github.com/evnix/boltdbweb
```

##### Usage
```
boltdbweb --db-name=<DBfilename>[required] --port=<port>[optional]
```
- `--db-name` or `--d` The file name of the DB.
    - NOTE: If 'file.db' does not exist. it will be created as a BoltDB file.
- `--port` or `--p` Port for listening on... (Default: 8098)


##### Example
```
boltdbweb --d=test.db
```
Goto: http://localhost:8098

##### Screenshots:

![](https://github.com/evnix/boltdbweb/blob/master/screenshots/1.png?raw=true)

![](https://github.com/evnix/boltdbweb/blob/master/screenshots/2.png?raw=true)

![](https://github.com/evnix/boltdbweb/blob/master/screenshots/3.png?raw=true)
