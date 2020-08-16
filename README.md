# E-commerce Back End
A backend e-commerce API

[Walkthrough-Tutorial](https://drive.google.com/file/d/1qzqBGVWardWbyQiiaOtmTZT-zggzaNGI/view)

<img src ="images\ecommerce-insomnia.jpg">

## Installation

Clone project to local directory and cd into the correct directory. Run 'npm install' to install all dependencies included in the project.

## Usage

Create a .env file to store your environmental variable such as your MySQL username and password. Store your variables in the following form:

    DB_NAME='your_database_name'
    DB_USER='your_username"
    DB_PW='your_mysql_password'

Open your MySQL shell by typing 'mysql -u root -p' in the command line. When prompted, type in your password. Once in the shell, run 'mysql source db/schema.sql' to create your database. Run 'mysql show databases;' to ensure the database was created. Run 'mysql quit;' to quit the shell. Once out of the shell, run 'npm run seed' to see the database with data. Once you have completed that, you may start your server by typing 'npm start' command in the terminal. You may now begin making api request.

## Questions

[GitHub](https://github.com/brandonmcguire1992)

[Email](mailto:brandonmcguire1992@gmail.com)