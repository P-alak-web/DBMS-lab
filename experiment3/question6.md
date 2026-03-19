## 6. Display employee number and names for employees who earn commission.

### Query
```sql
SELECT empno, ename FROM Employee 
WHERE comm IS NOT NULL;
```

### Output
Displays employee number and name of employees who receive commission.
![alt text](image-5.png)