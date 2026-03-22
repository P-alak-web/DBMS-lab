
## 13. Employees joined before 15 months

### Query
```sql
SELECT * FROM emp
WHERE day(hiredate) > 15;
```

### Output
| EMPNO | ENAME |
|-------|-------|
| 7369  | SMITH |

---

![alt text](image-11.png)