## 3. Display your age in months

### Query
```sql
SELECT TIMESTAMPDIFF(MONTH,'2006-05-19',CURDATE()) AS age_in_months;
```

### Output
| AGE_IN_MONTHS |
|---------------|
| 238           |

---

![alt text](image-1.png)