How to run this project
Clone this project
Open with Postman / Command Shell
Run Command:
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
Run Command for Report:
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
Technology used:
Postman
Newman
Prerequisite:
Jdk
Node Js
Newman
Html Report Library
Newman and Report Installation Process:
Newman Install Command:
npm install -g newman-reporter-htmlextra
Newman Html Report Install Command:
npm install -g newman-reporter-htmlextra
API Documentation:
https://documenter.getpostman.com/view/26899722/2s9XxtzbR4
Test case list:
Create Student
Create Data Sets Using the Dynamic Random Variables.

Response time below 300

Verify Crated Student Details
In the test case you need to validate the following field values:

First Name

Middle Name

Last Name

Date of Birth

Response time below 300

Update Student
In the test case you need to validate the following field values:

Successful Message

Response time below 300

Verify Verify Updated Student Details
In the test case you need to validate the following field values:

First Name

Middle Name

Last Name

Date of Birth

Response time below 300

Create Technical skills Create Student Address
In the test case you need to validate the following field values:

Successful Message

Response time below 300

Create a Student Address
In the test case you need to validate the following field values:

Successful Message

Response time below 300

Get the Student's Full Details
In the test case you need to validate the following field values:

First Name

Middle Name

Last Name

Date of Birth

Language

Year Of Experience

Last Used Date

House Number

City

State

Country

Std Code

Home Address

Mobile

Response time below 300

Delete Specific Student
In the test case you need to validate the following field values:

Response time below 300

Newman Report Summary:
