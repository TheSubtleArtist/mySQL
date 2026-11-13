# Weather Observation Station 4

```text
Find the difference between the total number of CITY entries in the table and the number of distinct CITY entries in the table. 

```

![Weather-Station-Table](resources/weather-station-table.jpg)  

```SQL
SELECT COUNT(CITY) - COUNT(DISTINCT(CITY)) FROM STATION;
```