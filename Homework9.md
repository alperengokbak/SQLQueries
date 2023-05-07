# HOMEWORK - 9

## Queries

1 - Please write the INNER JOIN query to see the city (city) and country (country) names together in the city table and country table.

2 - Please write the INNER JOIN query to see the payment_id together with the first_name and last_name names in the customer table and payment table.

3 - Please write the INNER JOIN query to see the rental_id together with the first_name and last_name names in the customer table and rental table.

</br>

## Solution

```1
SELECT country.country, city.city from city
inner join country on country.country_id = city.country_id;
```

```2
SELECT payment.payment_id, customer.first_name, customer.last_name FROM customer
inner join payment on payment.customer_id = customer.customer_id;
```

```3
SELECT rental.rental_id, customer.first_name, customer.last_name FROM customer
inner join rental on rental.customer_id = customer.customer_id;
```
