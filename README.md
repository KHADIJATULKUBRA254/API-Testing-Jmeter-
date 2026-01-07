Project Overview
This assignment demonstrates data-driven testing using Apache JMeter.
The test uses book data (title, author, type) and multiple user credentials to simulate requests and validate responses.

The goal is to understand how JMeter handles CSV data, user variables, and parameterized inputs.

Test Data Used
📚 Book Data
The following book records were used as input data:
Title	Author	                                     Type
The Alchemist                           	  Paulo Coelho	Fiction
The Lion The Witch and the Wardrobe	        C. S. Lewis	Fiction
Da Vinci Code	                              Dan Brown	Fiction
The Great Gatsby	                          F. Scott Fitzgerald	Fiction
The Prophet	                                Kahlil Gibran	Fiction

This data is read dynamically during test execution.
🔤 Parameters (a, b, c, d)
The parameters represent request variables used in the JMeter test:
a → Book Title
b → Author Name
c → Book Type
d → Additional request parameter / validation variable

These parameters are populated using CSV Data Set Config to avoid hard-coded values.
👤 User Credentials
Multiple users are simulated using CSV input:

u1   p1
u2   p2

Each thread picks a different username and password
This simulates multiple users accessing the system

🧪 What Was Performed
Configured CSV Data Set Config for book data
Configured CSV Data Set Config for user credentials
Sent requests using dynamic parameters (a, b, c, d)
Validated responses for correct data handling
Tested behavior under multiple user inputs

🎯 Key Learning Outcomes
Understanding data-driven testing in JMeter
Using CSV Data Set Config
Handling multiple users in performance testing
Parameterization of requests
Basic validation of API / application responses

Tools Used
Apache JMeter

Author
Khadija-Tul-Kubra
Software Quality Assurance Intern / Fresh Graduate
