# Display employee name and department name for each employee.



SELECT e.ENAME, d.DNAME
FROM EMPLOYEE e
JOIN DEPARTMENT d ON e.DEPTNO = d.DEPTNO;


# output
![alt text](image-8.png)