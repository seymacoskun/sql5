1. SELECT title FROM film
    WHERE LIKE '%n' ORDER BY length DESC
    LIMIT 5;

2. SELECT title FROM film
    WHERE LIKE '%n' ORDER BY length
    OFFSET 5
    LIMIT 5;

3. SELECT last_name FROM customer
    ORDER BY DESC
    store_id = 1 
    LIST 4;
