# POSTGRESQL
In this code, I was using the SELECT DISTINT keyword to return only the distinct values in the column i wanted.
In the second part of the code i was using the COUNT to return back a  count of the number of rows in that specific table.




SELECT * FROM film;
SELECT DISTINCT (release_year) FROM film;
SELECT DISTINCT (rental_rate) FROM film;
SELECT DISTINCT (rating) FROM film;

"release_year"
2006


"rental_rate"
2.99
4.99
0.99

"rating"
"R"
"NC-17"
"G"
"PG"
"PG-13"


/*count*/

SELECT * FROM payment;
SELECT COUNT (*) FROM payment;
SELECT (amount) FROM payment;
SELECT DISTINCT amount FROM payment;
SELECT COUNT (DISTINCT amount) FROM payment;

