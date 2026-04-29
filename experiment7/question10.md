# Display the depart numbers and total salary for each department.


SELECT DEPTNO, SUM(SAL) AS TOTAL_SALARY
FROM EMPLOYEE
GROUP BY DEPTNO;


# output

![alt text](image-10.png)