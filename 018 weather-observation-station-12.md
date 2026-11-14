# Weather Observation Station 11

```text
Query the list of CITY names from STATION that do not start with vowels and do not end with vowels. Your result cannot contain duplicates.
```

![Weather-Station-Table](resources/weather-station-table.jpg)  

```SQL
SELECT DISTINCT(CITY) FROM STATION WHERE LOWER(SUBSTRING(CITY, 1, 1)) NOT IN ('a', 'e', 'i','o','u') AND LOWER(SUBSTRING(CITY, -1, 1)) NOT IN ('a', 'e', 'i','o','u');
```