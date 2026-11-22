# ATM-System

A desktop ATM application built with Java Swing and a MySQL database. Users can create an account, sign in with a PIN, and manage their money.
Features
Sign up and sign in
Deposit, withdraw, and check balance
Two account types built with OOP (an Account interface):
Checking account with an overdraft limit of 1000
Saving account with a limit of 3 withdrawals
Data stored in MySQL through JDBC
Graphical interface built with Java Swing
Tech Stack
Java, Swing, MySQL, JDBC, Maven
How to Run
Install Java and MySQL (XAMPP works).
Create a database named atm_users_database and import atm_users_database.sql.
Open the project in NetBeans or IntelliJ and run ATM_System.java.
The database connection uses localhost:3306 with user root (edit it in the source if yours is different)
