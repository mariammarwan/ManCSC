# Solving the SQL Problems

Q1. SELECT * FROM CITY WHERE POPULATION > 100000 AND COUNTRYCODE = 'USA';

Q2. SELECT name FROM Employee ORDER BY name ASC

Q3. SELECT tweet_id FROM Tweets WHERE LENGTH(content) > 15

Q4. UPDATE Salary SET sex = CASE 
    WHEN sex = 'f' THEN 'm'
    WHEN sex = 'm' THEN 'f' 
END;
