# Select dept name, dept no and sum of sal

SELECT d.DEPTNO, d.DNAME, SUM(e.SAL) AS TOTAL_SAL
FROM EMPLOYEE e
JOIN DEPARTMENT d ON e.DEPTNO = d.DEPTNO
GROUP BY d.DEPTNO, d.DNAME;






# output

![alt text](image-7.png)