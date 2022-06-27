# API Testing With Postman and Newman
This project is to test a API with many operations including Authentication, Token Generation, CRUD and search functionalities. 

Frist I have tested this in Postman. Created many tested cases for testing all end points with predefined test scripts and environtment settings. 
When all test cases passed, I have exported the collection as JSON.

I have then created a Newman project using NPM and added the Postman Collected JSON. I've added the necessary
code to generate the report in Newman.

## Installation 
Clone the repo in your local. Then run the following command to install the project with necessary dependencies.

`npm install`

## Run the project using Newman

`npm test`
