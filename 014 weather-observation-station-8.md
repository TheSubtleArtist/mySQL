# Weather Observation Station 8

```text
Query the list of CITY names from STATION which have vowels (i.e., a, e, i, o, and u) as both their first and last characters. Your result cannot contain duplicates.
```

![Weather-Station-Table](resources/weather-station-table.jpg)  

```SQL
SELECT DISTINCT(CITY) FROM STATION WHERE LOWER(SUBSTRING(CITY, 1, 1)) IN ('a', 'e', 'i','o','u')
    AND LOWER(SUBSTRING(CITY, -1, 1)) IN ('a', 'e', 'i','o','u');
```