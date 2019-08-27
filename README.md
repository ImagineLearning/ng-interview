# Imagine Learning FrontEnd Interview

An Angular Coding Exercise

## Purpose
To demonstrate proficiency in developing a simple web application with the Angular framework.

## Expectations
To complete this exercise, you will need a working knowledge of Angular, as well as familiarity with Git and Node.js. There is no set time limit on the project, but ideally it should take less than an hour.

In the end, you will provide a link to a GitHub repository containing the working implementation of the requirements specified below.

## Getting Started
This repository is an application to get you started. Follow the instructions [outlined](REPOINFO.md) to to set up your development environment.

## Requirements
Listed below are the features that should be completed with this project. You should also include a set of unit tests which demonstrate your solution adequately meets the requirements.

## Students API Service
As an education company, we deal with student data a lot. We have a simple API for you to query sample student data to use in your application.

Implement a function in StudentsService (app/services/api/students/students.service.js) to retrieve a list of students from http://il-resume-api.azurewebsites.net/api/students. 

We should warn you though, the API has some issues. Sometimes it gets bogged down and will return a 503 Service Unavailable error. When that happens, your application should automatically retry the request. This problem may exist with other API endpoints as well, so you should implement a solution that can be easily reused.

Additionally, from time to time the API will give back invalid JSON. Be sure your application handles such responses appropriately and doesn't just blow up.

## Students View
Once you have your service implemented to retrieve student data, you’ll want to hook it up to the students view (app/students) of the application. In the view, display a list of student names. When the user clicks on a student’s name, it will display the additional information about the student provided in the JSON.

Make sure you’ve handled errors appropriately, and notify the user of an error in the UI if necessary.

## Students Filter
Once you have a list of students displayed in the students view, add a search field above your list of students. Users can type text into the search field, and the list of students will be limited to only the students whose names match (or partially match) the search text.

## Project Submission
Push your changes to your forked repository on GitHub, then email us a link to your repository. Please make sure the repository is not private so we can view your code. We look forward to reviewing what you’ve done!
