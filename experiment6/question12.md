## 12. Employees whose 10% salary = joining year

### Query
```sql
SELECT * from employee WHERE LEFT(YEAR(hiredate),2) = RIGHT(CAST(Sal AS CHAR),2);
```

### Output
| No rows |


![alt text](image-10.png)