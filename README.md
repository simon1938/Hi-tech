# Project - Hi-tech Site - Installation Guide

This guide will explain how to install and run this project, a marketplace website for tech products.

## Installation Steps

1. Downloading and extracting the project:
   - Download the project from [https://github.com/cocoutbm/Angular-Shop-WE4B]
   - Extract the files to the directory of your choice.

2. Installing frontend dependencies:
   - Open a terminal and navigate to the project directory "Angular-Shop-WE4B"
     ```
     cd .\frontend\
     ```
   - Run the following command to install the necessary dependencies:
     ```
     npm install
     ```

3. Launching the frontend:
   - Still in the same terminal, run the following command:
     ```
     ng serve
     ```
   - The Angular development server will start, and the site will be accessible at [http://localhost:4200](http://localhost:4200).

4. Launching the database server (json-server):
   - Open another terminal.
   - Navigate to the project directory "Angular-Shop-WE4B"
     ```
     cd .\frontend\
     ```
   - Run the following command to start the database server:
     ```
     json-server --watch mydb.json
     ```

## Login Accounts

Use the following information to log in to different accounts:

- Seller:
  - Email: aubin.bonnefoy@utbm.fr
  - Password: mdpaubin

- Buyer:
  - Email: toto@mail.com
  - Password: azerty

That's it! You are now ready to use the Hi-tech Site.
Enjoy!
