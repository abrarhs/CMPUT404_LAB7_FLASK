Question 0: What is the URL of your python flask_restfull code on github???
https://github.com/abrarhs/CMPUT404_LAB7_FLASK

Question 1: How are Flask and Django different? What does Django provide for you that Flask does not?
The main difference betwen the two is that Flask provides support for API, while Django doesn’t have any support for API. Also, Flask does not support dynamic HTML pages, whereas Django offers dynamic HTML pages.

Question 2: What does REST stand for? When I say something is RESTful, what does that mean?
Representational State Transfer. RESTful API means that two computer systems can exchange information securely over the internet. Also, the requests are stateless.

Question 3: What does CRUD stand for? For each letter in CRUD, give the associated HTTP method.
CREATE - POST 
READ - GET 
UPDATE - PUT 
DELETE - DELETE

Question 4: What do HTTP 1XX Status Codes mean? HTTP 2xx? HTTP 3xx? HTTP 4xx? HTTP 5xx?
100 - give informational responses
200- success responses
300- redirection responses
400 - client error responses
500 - server error responses

Question 5: What is an XSS attack? Provide one way a site can be vulneratble to an XSS attack.
A XSS (Cross Site Scripting) attack is when a malicious script is injected into a trusted website. A site can be vulnerable to an XSS attack if it uses unsanitized user input.

Question 6: What does CORS stand for? What situation in web application development will you need to implement CORS protection?
Hint: What does the CO part of CORS mean?
Cross-Origin Resource Sharing. CORS Protection will be useful when you don't want servers to load information from domains other than its own.