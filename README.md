Tuum API TEST,

All the tests have been done via postman (Newman), for testing I used some JS also for reporting html reporter has been used.

Required application:
Postman
Node.js
Newman
html reporter 

Steps to run the test:

Install node.js
Install Newman using CLI
Install html reporting using CLI 
before running the test open the .json file and change the "idNumber" param value, as this value should be unique
Run the test (newman run filename.json --reporters cli,htmlextra)
After the test is done, open the new man folder and the report should be there.

In case of any question or comment please contact me at khanrifaq@gmail.com.
