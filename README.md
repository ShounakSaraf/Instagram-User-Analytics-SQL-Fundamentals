# Instagram-User-Analytics-SQL-Fundamentals
Sql Project prolems Instagram User Analytics SQL Fundamentals

Q.1 Identify the five oldest users on Instagram from the provided database.

Query : 
       select * from users
                  order by created_at 
                  limit 5;
