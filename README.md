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

## Documentation

Here is the link of the Postman Documentation

https://documenter.getpostman.com/view/8819557/UzBtn3y8

## Reports

This is a Screenshot of reports

![Capture_reports](https://user-images.githubusercontent.com/108174180/176270595-529f106f-dd09-4556-bc3a-8eb4736af141.PNG)



