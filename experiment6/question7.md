## 7. Nearest Saturday after current date

### Query
```sql
SELECT DATE_ADD(CURDATE(), INTERVAL(7- DAYOFWEEK(CURDATE()) + 7) % 7 DAY) AS NEXT_SATURDAY;
```

### Output
| NEXT_SATURDAY|
|----------|
| 2026 - 03 - 21 |

---

![alt text](image-6.png)
