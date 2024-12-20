* After cloning the repository.
* Rename the "example.env" to ".env" and configure it.
* Open your xampp then run mysql
* Create your database then creates "users" table
  
| Column Name     | Data Type        | Description                 |
|-----------------|------------------|-----------------------------|
| uid             | INT              | Primary Key, Auto Increment |
| username        | VARCHAR(255)     | Unique, Not Null            |
| password        | VARCHAR(255)     | Not Null                    |

* SQL Statement to Create the users Table
CREATE TABLE users (
  uid INT AUTO_INCREMENT PRIMARY KEY,
  username VARCHAR(255) NOT NULL UNIQUE,
  password VARCHAR(255) NOT NULL
);
