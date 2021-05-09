# SQL Details  

This directory has base data for our project.  

## Creation  
- Make a Database called *restaurant* with details in the [database.js](../code/database.js) file
- Run [tables.sql](tables.sql) to create the relations

## Insertion  
Run the other sql files to insert tuples in the following order: (order is such that all foreign key violations are avoided)  
- [accounts.sql](accounts.sql)
- [ingredients.sql](ingredients.sql)
- [dishes.sql](dishes.sql)
- [customers.sql](customers.sql)
- [customer_contact.sql](customer_contact.sql)
- [staff.sql](staff.sql)
- [staff_contact.sql](staff_contact.sql)
- [sitting.sql](sitting.sql)
- [contains.sql](contains.sql)
- [orders.sql](orders.sql)
- [cooks.sql](cooks.sql)
- [payment.sql](payment.sql)
- [tracks.sql](tracks.sql)
- [delivers.sql](delivers.sql)
- [pay_by.sql](pay_by.sql)