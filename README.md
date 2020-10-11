# HackerRank_SQL

[Type Of Triangle](https://www.hackerrank.com/challenges/what-type-of-triangle/problem)<br/>
**Solution:**
SELECT 
CASE
     WHEN A+B <= C OR B+C <= A OR A+C <= B THEN 'Not A Triangle'
     WHEN A=B AND B=C THEN 'Equilateral'
     WHEN A=B OR B=C OR C=A THEN 'Isosceles'
     WHEN A<>B AND B<>C AND C<>A THEN 'Scalene' 
     END 
FROM TRIANGLES; 
