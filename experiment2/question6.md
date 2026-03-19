## 6. Find all managers not in department 30.

### Query
```sql
SELECT * FROM Employee 
WHERE job = 'MANAGER' AND deptno <> 30;
```

### Output
Displays all managers who are not working in department 30.
![alt text](image-6.png)