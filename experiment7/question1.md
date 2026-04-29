# Compute the no. of days remaining in this year.


SELECT 
DATEDIFF(
    MAKEDATE(YEAR(CURDATE()) + 1, 1),
    CURDATE()
) AS DAYS_REMAINING;


# output

![alt text](image.png)