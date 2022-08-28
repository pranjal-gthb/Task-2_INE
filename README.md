# Task-2_INE

The web application allows users to search customer’s detail.

Link to Launch Web Application (_Please use Laptop, and the input is Case Sensitive so plaese lookout_): http://getcustdeta.s3-website.us-east-2.amazonaws.com

DataBase contains the following items:

<img width="777" alt="Screenshot 2022-08-29 at 12 09 48 AM" src="https://user-images.githubusercontent.com/68143657/187090195-258fe55f-8bbe-45f3-9791-85c7a7673bb9.png">


Upon providing the first name or last name of the customer, the application will return the following information if the customer exists in the database:

● First Name 

● Last Name 

● Phone Number 

● Age 

● Address

The DynamoDB database must-have details of at least 5 customers and any programming language can be used for the lambda function.

Vulnerability:

Upon performing a search, the web page displays the result on the same page in a section beneath the search input field.

The web page also shows a string '_Showing Results for "<search_input>"_.' (For clarity, refer to the wireframe provided below).

The web application is vulnerable to reflected XSS attack and upon injecting an XSS payload in the input field the payload will be executed.
