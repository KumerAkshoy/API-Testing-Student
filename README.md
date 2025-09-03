# API-Testing-Student
This project demonstrates API testing using Postman, providing a collection of tests to validate various endpoints of the API.

## Features
<ul>
  <li>Tests for GET, POST, PUT, PATCH, DELETE requests</li>
  <li>Collection of tests covering different API endpoints</li>
  <li>Environment setup for easy switching between environments</li>
  <li>Pre-request scripts for data setup</li>
  <li>Test scripts for assertions and validations</li>
</ul>

##  Technology used:
<ul>
  <li>Postman</li>
  <li>Newman</li>
</ul>

##  Prerequisite:
<ul>
  <li>Node Js</li>
  <li>Newman</li>
  <li>Newman Html Report Library</li>
  </ul>

## Steps to Produce: 
=> Create a json file, [student.json] <br>
=> Activate the server and copy the url to postman. [cmd prompt: json-server student.json] <br>
=> Test for GET, POST, PUT, PATCH, DELETE requests. <br>
=> Write Pre-request script and post request script for the methods. <br>
=> Run the collection. <br>
=> Export the postman collection file in you local machine. <br>
=> Run the postman collection in newman. [cmd prompt: newman run file_name] <br>
=> Install the Newman HTML extra report file. [cmd prompt: npm install -g newman-reporter-htmlextra] <br>
=> Generate the Newman HTML extra report. [cmd prompt: newman run collection.json -r htmlextra] <br>  
## newman-HTML-Report

<img width="800" height="800" alt="image" src="Newman HTML report image/SC1.jpg" />
<img width="800" height="700" alt="image" src="Newman HTML report image/SC2.jpg" />
<img width="800" height="400" alt="image" src="Newman HTML report image/SC3.jpg" />
