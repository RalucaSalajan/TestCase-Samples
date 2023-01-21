# TestCase-Samples

Below are some Test Cases Samples that I wrote for my previous projects.

**Project 1-> wordpress.com**

*Title*: Test login with correct credentials

*Description*: Test the login by using the correct credentials.

*Steps to reproduce*:
1. Go to wordpress.com/login.
2. Add a correct user and password.
3. Press the "Login" button.

*Expected Result*: User is able to log in.

*Test Data*:User: ralukamoldovan@yahoo.com & Pass: Iarna123.

-----------------------------------------------------------------------

*Title*: Test login with incorrect credentials

*Description*: Test the login by using incorrect credentials.

*Steps to reproduce*:
1. Go to Go to wordpress.com/login
2. Add an incorrect user and password
3. Press the ""Login"" button

*Expected Result*: The user is not able to log in.

*Test Data*: User: ralukamoldovan@yahoo.com & Pass: Iar123.

-----------------------------------------------------------------------

*Title*: Test login with "Remember me" box tick

*Description*: Test the login by using the"remember me" tick.

*Steps to reproduce*:
1. Go to wordpress.com/login
2. Leave empty the email address
3. Press ""Login"" button
4. Close the site
5. Reopen the site

*Expected Result*: The user is logged in with his credentials when he reopens the site.

*Test Data*: User: ralukamoldovan@yahoo.com & Pass: Iarna123.

-----------------------------------------------------------------------

**Project 2-> emag.com**

*Title*: Test search for an existing product

*Description*: Test the search by using an existing product.

*Steps to reproduce*:
1. Go to emag.ro
2. Add an existing product
3. Press ""Search"" button

*Expected Result*: The product is listed.

*Test Data*: product name : geluri de dus

----------------------------------------------------------------------------

*Title*: Test search a nonexistent product or several letters are written wrongly

*Description*: Test the search by using an inexisting product.

*Steps to reproduce*:
1. Go to emag.ro
2. Add an inexisting product.
3. Press "Search" button.

*Expected Result*: The site is showing 0 results and offers you suggestions of correcting your product name.

*Test Data*: product name : gogogo or trwciuryyyyy

-----------------------------------------------------------------------------

*Title*: Test search an incorrect name product

*Description*: Test the search by using one letter incorrect in the name of the product.

*Steps to reproduce*:
1. Go to emag.ro
2. Add an existing product, written incorrectly.
3. Press the ""Search"" button.

*Expected Result*:The site is showing 0 results and offers you suggestions for correcting your product name and a list of the products.

*Test Data*: product name : trwcouri.
