# Revising the Select Query 1

```text

Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.

The CITY table is described as follows: 
```

![City-Information](resources/revise-the-select-query-1.jpg)

```SQL
SELECT * FROM CITY WHERE CITY.COUNTRYCODE = 'USA'AND CITY.POPULATION > 100000;
```
