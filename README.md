# Task-2_INE

The web application allows users to search customer’s detail.

Upon providing the first name or last name of the customer, the application will return the following information if the customer exists in the database:
● First Name 
● Last Name 
● Phone Number 
● Age 
● Address 
The DynamoDB database must-have details of at least 5 customers and any programming language can be used for the lambda function.

Vulnerability:

Upon performing a search, the web page displays the result on the same page in a section beneath the search input field. The web page also shows a string 'Showing Results for "<search input>".' (For clarity, refer to the wireframe provided below). The web application is vulnerable to
reflected XSS attack and upon injecting an XSS payload in the input field the payload will be executed.
