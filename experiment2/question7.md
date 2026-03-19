## 7. List information about all Employees in department 10 who are not manager or clerks.

### Query
```sql
SELECT * FROM Employee 
WHERE deptno = 10 AND job NOT IN ('MANAGER', 'CLERK');
```

### Output
Displays employees in department 10 excluding managers and clerks.
![alt text](image-7.png)