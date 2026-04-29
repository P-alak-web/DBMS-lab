# List employee whose commission is greater than 25 % of their salaries.

SELECT ENAME, SAL, COMM
FROM EMPLOYEE
WHERE COMM > (SAL * 0.25);



# output

![alt text](image-2.png)