
Understanding the project
Reading through the code
Now you need to take some time to understand what the code is doing. It is a REST application with a python backend, if you do not know what a REST application is, it is simply as follows:  

“An application that implements CRUD functionality through HTTP requests” 

CREATE 
READ 
UPDATE 
DELETE 
Their request counterpart (In order): 

HTTP POST 
HTTP GET 
HTTPS PUT 
HTTP DELETE 
Have a read through the lbg.py file in the main directory, this is Python Flask, and all the routes (endpoint URL) should be in here for each of the four requests, there may be more than one route implementing the same request (such as GET). 

Read through the functions and see what they are implementing and how it is achieved through Python. You should notice that each function that is accessible via the web browser has an app.route decorator such as this:



This will tell you what URL you need to access to run the function and the methods that you use to access, in this case it would be something like: 

http://localhost/create (While pushing a POST request) 

This is a Dummy info to populate the text file
