# HOMEWORK - 11

## Queries

1 - Let's list all the data for the first_name columns found in the actor and customer tables.

2 - Let's list the intersecting data for the first_name columns found in the actor and customer tables.

3 - Let's list the data found in the first_name columns in the actor table, but not in the customer table.

</br>

## Solution

```1
(SELECT first_name FROM customer)
UNION ALL
(SELECT first_name FROM actor);
```

```2
(SELECT first_name FROM customer)
INTERSECT
(SELECT first_name FROM actor);
```

```3
(SELECT first_name FROM customer)
EXCEPT
(SELECT first_name FROM actor);
```
