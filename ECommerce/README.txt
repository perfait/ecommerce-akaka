In the htdocs folder, create a folder called ECommerce and inside it, copy all the files in this project. (NOTE: if you do otherwsie it won't run)

After saving, start your localhost server and create a database called db_ecommerce. I've attached it's scripts (db_ecommerce.sql) in this folder so all you have 
to do is import. If importation fails then then copy the scripts from db_ecommerce.sql file and paste them in the sql section in php my admin in browser.

After your done with the database, browse for localhost/ECommerce in browser to access the user side and localhost/ECommerce/admin for the admin side.


ADMIN CREDENTIALS (since it is unrealistic for an admin to  create an account. Adminship must be granted)

USER: akaka
pass: akaka

Once you're in, you can create other admin accounts.
An admin can create and remove other accounts
An admin can also change his/her profile picture


As a customer, you can create an account then log in.
All passwords are encrypted.

for you to access the cart, you must sign in or sign up.

When a customer checks out an order from the cart successfuly, the order request will appear in the admin side. The state of the order will remain as pending until 
approved by the admin, which then turns to confirmed.