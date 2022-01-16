# postgreSQL_odev9
PostgreSQL -  Dokuzuncu ödev - Ilgar Babashli

# _Q1_ 
city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

# _Ans_
SELECT city, country FROM city 
INNER JOIN country ON city.country_id = country.country_id;

# _Q2_ 
customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

# _Ans_
SELECT payment_id, first_name, last_name FROM customer 
INNER JOIN payment ON customer.customer_id = payment.customer_id;

# _Q3_ 
customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.


# _Ans_
SELECT rental_id, first_name, last_name FROM customer 
INNER JOIN rental ON customer.customer_id = rental.customer_id;

