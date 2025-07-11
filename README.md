
<h1>Steps to Create Database and Tables inside database after login:</h1> 
'''
SHOW DATABASES;
CREATE DATABASE IF NOT EXISTS usersinfo;
USE usersinfo;

CREATE TABLE IF NOT EXISTS your_table (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL UNIQUE
);

INSERT INTO your_table (name, email) VALUES ('Alice Smith', 'alice@example.com');

SELECT * FROM users;
'''