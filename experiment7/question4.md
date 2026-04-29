# Make a query that displays salary in dollar format.

SELECT ENAME,
CONCAT('$', FORMAT(SAL, 2)) AS SALARY_IN_DOLLAR
FROM EMPLOYEE;


# output

![alt text](image-3.png)