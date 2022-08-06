# POSTGRESQL PORTFOLIO
In this code, I was using the SELECT DISTINT keyword to return only the distinct values in the column i wanted.
In the second part of the code i was using the COUNT to return back a  count of the number of rows in that specific table.
Also the second part of the code,all the query below resulted in the same answer.
In the 3rd part of the code, I wanted to find a phone number of a customer from their address.
In the 4th part of the code I was using the ORDER BY statement from a Customer table to find first and last name and to order by ASC or DESC

 

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

"count"
19

SELECT phone FROM address
WHERE address ='259 Ipoh Drive';

"phone"
"419009857119"

SELECT store_id,first_name,last_name FROM customer
ORDER BY store_id DESC, first_name ASC;

"store_id","first_name","last_name"
2,"Aaron","Selby"
2,"Adrian","Clary"
2,"Agnes","Bishop"
2,"Alberto","Henning"
2,"Alex","Gresham"
2,"Alexander","Fennell"
2,"Alfred","Casillas"
2,"Alfredo","Mcadams"
2,"Allen","Butterfield"
2,"Allison","Stanley"
2,"Alvin","Deloach"
2,"Amanda","Carter"
2,"Ana","Bradley"
2,"Andrew","Purdy"
2,"Andy","Vanhorn"
2,"Angela","Hernandez"











