# HOMEWORK 2

## Queries

1 - Please arrange all the data in the columns of the film table with the condition that the replacement cost value is greater than or equal to 12.99 and less than 16.99 (use the BETWEEN - AND structure).

2 - Arrange the data in the first_name and last_name columns of the actor table with the condition that the first_name is 'Penelope' or 'Nick' or 'Ed' (use the IN operator).

3 - Arrange all the data in the columns of the film table with the conditions that rental_rate is 0.99, 2.99, 4.99 AND replacement_cost is 12.99, 15.99, 28.99 (use the IN operator).

</br>

## Solution

1 -
```
SELECT * FROM film
WHERE replacement_cost BETWEEN 12.99 AND 16.99;
```
</br>
2 -

```
SELECT first_name, last_name FROM actor
WHERE first_name in ("Penelope", "Nick", "Ed");
```
</br>
3 -

```
SELECT * FROM film
WHERE rental_rate in (0.99, 2.99, 4.99) AND replacement_cost in (12.99, 15.99, 28.99);
```
