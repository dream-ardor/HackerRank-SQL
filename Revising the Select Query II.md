Query the names of all American cities in CITY with populations larger than 120000. The CountryCode for America is USA.

**SOLUTION:**
```SQL
SELECT name FROM city WHERE population > 120000 AND CountryCode='USA';
