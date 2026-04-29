 # Display employee name, his job, his dept name, his manager name, his grade and make out of an under department wise


CREATE TABLE SALGRADE (
    GRADE CHAR(1),
    LOSAL INT,
    HISAL INT
);

INSERT INTO SALGRADE VALUES
('A', 700, 1200),
('B', 1201, 1400),
('C', 1401, 2000),
('D', 2001, 3000),
('E', 3001, 9999);

SELECT e.ENAME, e.JOB, d.DNAME, m.ENAME AS MANAGER, s.GRADE
FROM EMPLOYEE e
JOIN DEPARTMENT d ON e.DEPTNO = d.DEPTNO
LEFT JOIN EMPLOYEE m ON e.MGR = m.EMPNO
JOIN SALGRADE s ON e.SAL BETWEEN s.LOSAL AND s.HISAL
ORDER BY d.DNAME;











