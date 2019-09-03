# ng-interview — a sample Angular app

## TL;DR

1. Fork this repository on GitHub
2. Run `npm install`
3. Run `npm start`
4. Browse to [http://localhost:4200](http://localhost:4200/)

## Introduction

This project is a simple [Angular](https://angular.io) web app for front end developer candidates.

The project is preconfigured to install the Angular framework and a bunch of development and testing tools
for quickly setting up your development environment.

The app doesn't do much, that part is up to the applicant.

## Getting Started

To get you started you can simply fork the [ng-interview][ng-interview] repository, clone it locally, and install the dependencies.

### Prerequisites

You need to have git installed locally so you can clone your fork of the ng-interview repository. You can get git from
[http://git-scm.com/](http://git-scm.com/).

You must have node.js and its package manager (npm) installed.  You can get them from [http://nodejs.org/](http://nodejs.org/).

### Fork and Clone ng-interview

Fork the [ng-interview][ng-interview] repository on GitHub.
If you are unfamiliar with forking, [follow these instructions](http://lmgtfy.com/?q=how+to+fork+a+repo+in+github).

Then clone your repository locally using git:

```
git clone https://github.com/YOUR-USERNAME/ng-interview.git
cd ng-interview
```

*Note: Be sure to replace the URL with the correct URL to your forked repository.*

### Install Dependencies

Installing the dependencies to this project is as simple as 

```
npm install
```

You should find that you have one new folder in your project.

* `node_modules` - contains the npm packages for the tools we need

*Note that the running `npm install` will set you up with angular cli which we hope you would use.*

### Run the Application

This application was generated via angular cli.  The application is preconfigured with a simple development web server.  The simplest way to start
this server is:

```
npm start
```

and can be viewed at `http://localhost:4200`.

## Testing

There are two kinds of tests in the ng-interview application: Unit tests and end-to-end tests.  For this exercise we will disregard the end-to-end tests.

### Running Unit Tests

The easiest way to run the unit tests is to use the supplied npm script:

```
npm test
```

### Checking Code Coverage

Code coverage is something we value here at Imagine Learning.  Angular comes with code coverage report which we have enabled.

The following command should generate a coverage folder with details of the report which should be accessible by opening the `coverage/ng-interview/index.html` file in your browser.

```
npm test:code-coverage-report
```

## Contact

For more information on Angular please check out [https://angular.io](https://angular.io)

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
