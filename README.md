# day2
database day 2

CREATE DATABASE IF NOT EXISTS sales;

USE sales;

CREATE TABLE IF NOT EXISTS orders (
order_id INT PRIMARY KEY AUTO_INCREMENT,
customer_id INT NOT NULL,
order_date DATE NOT NULL,
order_total DECIMAL(10,2) NOT NULL
);
