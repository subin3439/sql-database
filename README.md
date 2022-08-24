# sql-database


[9:04 pm, 24/08/2022] Aswin relative: CREATE TABLE Customers( CustomerID int, CustomerName CHAR(50), ContactName CHAR(50), Address CHAR(50),
[9:05 pm, 24/08/2022] Aswin relative: INSERT INTO Customers (customerid, customername, contactname, address, city, country)
VALUES ('1', 'Alfreds Futterkiste', 'Maria Anders', 'Obere Str.57', 'Berlin', 'Germany');





                                   ^
postgres=# CREATE TABLE Employe(customer_id INT PRIMARY KEY,customer_name VARCHAR(100)NOT NULL,contact_name VARCHAR(100)NOT NULL,address VARCHAR(100)NOT NULL,city VARCHAR(100)NOT NULL,postal_code INT ,country VARCHAR(100)NOT NULL);
CREATE TABLE
postgres=# INSERT INTO Employe(customer_id,customer_name,contact_name,address,city,postal_code,country) VALUES(1,'subinjoseph','subin','fathimanagar','kollemcode','629160','kerala');
INSERT 0 1
postgres=# INSERT INTO Employe VALUES(2,'chellapan','soman','fathimanagar','kollemcode','629160','kootamala');
INSERT 0 1
postgres=# INSERT INTO Employe VALUES(3,'thangasily','chellamma','fathimanagar','kollemcode','629160','kootamala');
INSERT 0 1
postgres=# INSERT INTO Employe VALUES(4,'poozhiyur sindu','suni','fathimanagar','kollemcode','629160','kootamala');
INSERT 0 1
postgres=# SELECT * FROM Employe;
 customer_id |  customer_name  | contact_name |   address    |    city    | postal_code |  country  
-------------+-----------------+--------------+--------------+------------+-------------+-----------
           1 | subinjoseph     | subin        | fathimanagar | kollemcode |      629160 | kerala
           2 | chellapan       | soman        | fathimanagar | kollemcode |      629160 | kootamala
           3 | thangasily      | chellamma    | fathimanagar | kollemcode |      629160 | kootamala
           4 | poozhiyur sindu | suni         | fathimanagar | kollemcode |      629160 | kootamala
(4 rows)

