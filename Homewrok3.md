# HOMEWORK 3

## Queries

1 - Arrange the country names in the country column of the country table that start with the character 'A' and end with the character 'a'.

2 - Arrange the country names in the country column of the country table that consist of at least 6 characters and end with the character 'n'.

3 - Arrange the film names in the title column of the film table that contain at least 4 instances of the character 'T', regardless of upper or lower case.

4 - Arrange the data in all columns of the film table with the condition that the title starts with the character 'C', the length (length) is greater than 90, and the rental_rate is 2.99.

</br>

## Solution

1 -
```
SELECT country FROM country
WHERE country LIKE "A%a";
```
</br>
2 -

```
SELECT country FROM country
WHERE LENGTH(country) >= 6 AND country LIKE "%N";
```
</br>
3 -

```
SELECT title FROM film
WHERE title LIKE "%T%" AND LENGTH(title) >= 4;
```
</br>
4 -

```
SELECT * FROM film
WHERE title LIKE "C%" AND length > 90 AND rental_rate in (2.99);
```
