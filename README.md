# Sprint 7-Project-7 TASK
Task-5
1.This project was generated with node.js and npm jest version 20.11.1
2.By using the operating system is
  Windows 10

3.How to run this project:
 Clone the repository to my local directory and other steps
  
  1. git clone git@github.com:Pavanikunapreddy/hm07-qa-us.git
  2. npm install
  3. npx jest
  Before run the npx jest In config.js, replace the API URL with the link generated after the launch of Urban Grocers server. 
  link:https://cnt-0e84b7e7-4c4e-4933-ba73-44331a9e25a4.containerhub.tripleten-services.com/

4.Create a virtual environment to install project dependencies. You can do this by running the following command:
   1. open file and select the local folder and create on VS
   2. run the commands
     1.npm insatll
     2.npx jest

5.Code Style observed:
 camelCase is used for variable names and it's can be verify the variable
 1. let actualStatusCode; 
     -> we should return the status of the test by using this varaiable
 2 .let actualResponseBody;
     ->   Body should contains the particular reponses message of the test by using this varaiable
 3. const response
     -> while using this constant variable its not change the response   

6.To run the tests data by using the swaggar and Api docs 

7.Before doing on VS code we check on POSTMAN by using swaggar and API doc write tests for GET, POST, PUT, and DELETE requests.
 1.To Getting the data by using GET request
 2.To createing the data by using POST request
 3.To Update the data or Adding the data by using PUT request
 4.To delete the data by using DELETE request

8.After write the code to open a New Terminal and send the commands
 1.npx jest tests/deleteHandlers.test.js
 2.npx jest tests/getHandlers.test.js
 3.npx jest tests/postHandlers.test.js
 4.npx jest tests/putHandlers.test.js    
  
9.The tests will run, and I will see the results displayed in my terminal.
1. PASS  tests/deleteHandlers.test.js
  √ Response body should delete Ok True (534 ms)
  √ Status code should be 200 (136 ms)

Test Suites: 1 passed, 1 total
Tests:       2 passed, 2 total
Snapshots:   0 total
Time:        2.589 s, estimated 3 s

2. PASS  tests/getHandlers.test.js
  √ Should return 200 status code.... (553 ms)
  √ Body should contain...... (130 ms)

Test Suites: 1 passed, 1 total
Tests:       2 passed, 2 total
Snapshots:   0 total
Time:        2.485 s, estimated 3 s

3. PASS  tests/postHandlers.test.js
  √ Status code should be 201 (517 ms)
  √ Response body should be .... (183 ms)

Test Suites: 1 passed, 1 total
Tests:       2 passed, 2 total
Snapshots:   0 total
Time:        2.246 s, estimated 3 s

4. PASS  tests/putHandlers.test.js
  √ Status code should be 200  (542 ms)
  √ Response body should contains Ok True (149 ms)

Test Suites: 1 passed, 1 total
Tests:       2 passed, 2 total
Snapshots:   0 total
Time:        2.238 s, estimated 4 s
