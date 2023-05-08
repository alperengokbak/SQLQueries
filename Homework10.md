# HOMEWORK - 10

## Queries

1 - Write a LEFT JOIN query where we can see the city (şehir) and country (ülke) names together in the "city" and "country" tables.

2 - Write a RIGHT JOIN query where we can see the payment_id, first_name, and last_name together in the "customer" and "payment" tables.

3 - Write a FULL JOIN query where we can see the rental_id, first_name, and last_name together in the "customer" and "rental" tables.

</br>

## Solution

```1-
SELECT city.city, country.country FROM city
left join country on country.country_id = city.country_id;
```

```2-
SELECT payment.payment_id, customer.first_name, customer.last_name FROM customer
right join payment on payment.customer_id = customer.customer_id;
```

```3-
SELECT rental.rental_id, customer.first_name, customer.last_name FROM customer
left join rental on rental.customer_id = customer.customer_id
union
SELECT rental.rental_id, customer.first_name, customer.last_name FROM customer
right join rental on rental.customer_id = customer.customer_id;
```
