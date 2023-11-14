# Activity: Using Records App

Create directory scripts/data_init
Install Faker inside data_init directory
Add this to your .gitignore file
**/vendor
**/composer.json
**/composer.lock
Create load_data.php

Write a PHP script that will initially load fake data to your database.
Use Philippine Locale
Employee (200 rows) -> id, lastname, firstname, office_id, address
Office (50 rows)-> id, name, contactnum, email, address, city, country, postal
Transaction (500 rows) -> id, employee_id, office_id, datelog, action, remarks, documentcode
Random selection of FK should be from PK of reference table
Set max value for datelog (future dates are not allowed)

# CRUD ACTIVITY 

# April Joy Gamboa
# Desierre Lofranco
