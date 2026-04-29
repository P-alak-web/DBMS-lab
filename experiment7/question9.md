# Display the various jobs and total number of employees within each job group.


SELECT JOB, COUNT(*) AS TOTAL_EMPLOYEES
FROM EMPLOYEE
GROUP BY JOB;



# output

![alt text](image-9.png)