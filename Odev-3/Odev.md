select country from country where country like 'A%a';

select country from country where LENGTH(country) >= 6 and country like '%n'

select title from film where lower(title) ilike '%t%t%t%t%';

select * from film where title like 'C%' and length(title) > 90 and rental_rate = 2.99;
