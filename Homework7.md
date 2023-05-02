# HOMEWORK - 7

## Queries

1 - Group the films in the film table by their rating values.

2 - When grouping the films in the film table by the replacement_cost column, list the replacement_cost value and the corresponding film count for cases where the film count is greater than 50.

3 - What are the customer counts corresponding to the store_id values in the Customer table?

4 - After grouping the city data in the City table by the country_id column, share the country_id information with the highest city count and the city count.

</br>

## Solution

```1 -
SELECT title, rating FROM film
GROUP BY rating, title;
```

</br>

```2 -
SELECT replacement_cost, COUNT(*) FROM film
GROUP BY replacement_cost
HAVING COUNT(*) > 50;
```

</br>

```3 -
SELECT store_id, COUNT(*) FROM customer
GROUP BY store_id;
```

</br>

```4 -
SELECT country_id, COUNT(*) AS city_count FROM city
GROUP BY country_id
ORDER BY city_count DESC
LIMIT 1;
```
