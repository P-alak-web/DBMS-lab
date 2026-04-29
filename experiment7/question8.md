# Display department numbers and total number of employees working in each department.

SELECT DEPTNO, COUNT(*) AS TOTAL_EMPLOYEES
FROM EMPLOYEE
GROUP BY DEPTNO;



# output

![alt text](image-8.png)