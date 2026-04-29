# Query to get the last Sunday of Any Month.

SELECT 
DATE_SUB(
    LAST_DAY('2026-02-01'),
    INTERVAL (WEEKDAY(LAST_DAY('2026-02-01')) + 1) DAY
) AS LAST_SUNDAY;


# output

![alt text](image-7.png)