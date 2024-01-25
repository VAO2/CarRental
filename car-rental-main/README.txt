#Completed

# Project Installation Guide

## Prerequisites
- Node.js installed on your machine
- MySQL database installed and running
- npm package manager installed

## Installation Steps

1.  Install Dependencies 
     
   npm install
    

2.  Configure MySQL Database 
   - Open the `index.js` file.
   - Locate the `db.connect()` method.
   - Enter your MySQL database password in the method's parameters.

3.  Run Database Script 
   - Execute the DDL.sql file in your local MySQL database. This will set up the required tables and schema.
       
      

4.  Run the Application 
     
   npm run dev
    

5.  Access the website
   - Open your web browser.
   - Go to [http://localhost:3000]
