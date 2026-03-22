## 9. Date three months before today

### Query
```sql
SELECT DATE_SUB(CURDATE(), INTERVAL_3 MONTH) AS past_date;
```

### Output
| DATE |
|------|
| 22-DEC-25 |

---

![alt text](image-8.png)
