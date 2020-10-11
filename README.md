# HackerRank_SQL

[Type Of Triangle](https://www.hackerrank.com/challenges/what-type-of-triangle/problem)<br/>
**Solution:**<br/>
SELECT <br/>
CASE <br/>
     WHEN A+B <= C OR B+C <= A OR A+C <= B THEN 'Not A Triangle'<br/>
     WHEN A=B AND B=C THEN 'Equilateral'<br/>
     WHEN A=B OR B=C OR C=A THEN 'Isosceles'<br/>
     WHEN A<>B AND B<>C AND C<>A THEN 'Scalene' <br/>
     END <br/>
FROM TRIANGLES; 
