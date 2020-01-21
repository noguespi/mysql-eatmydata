# mysql-eatmydata

Mysql using eatmydata to speedup integration tests.

it will disable all call to fsync, data may be lost or corrupted at the end of the process. 

Use it only for testing.

Available versions : 

```
nogues/mysql-eatmydata:latest
nogues/mysql-eatmydata:8
nogues/mysql-eatmydata:5.7
nogues/mysql-eatmydata:5.6
```