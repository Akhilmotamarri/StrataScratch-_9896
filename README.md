# StrataScratch-_9896
StrataScratch 9896
select first_name from customers
WHERE id NOT IN 
(select DISTINCT cust_id from orders); 
