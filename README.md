# QAcart - Postman

This repository contains resources related to the project created as part of the "Postman" Course at QAcart. Here, you'll find the Postman collections and environments created throughout the course.

## Table of Contents

- [Introduction](#introduction)
- [Learning Milestones](#learning-milestones)
- [Technologies Used](technologies-used)
- [Directory Structure](#directory-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributions](#contributions)
- [Disclaimer](#disclaimer)

## Introduction

The "[Postman](https://qacart.com/course/postman)" course at QAcart is a great resource for learning and mastering APIs. From diving into the secrets of RESTful APIs to creating powerful and automated test suites, this course is a great guide for enhancing API testing skills in a way that's both engaging and easy to grasp.\
This repository houses the project developed and implemented throughout the course.

## Learning Milestones

- Building a server using [JSON Server](https://github.com/typicode/json-server).
- Setting environment variables.
- Mock the API with Postman.
- Building an Auth Server using [JSON Server Auth](https://www.npmjs.com/package/json-server-auth).
- Building E2E test cases.
- Running E2E test cases using Postman.
- Running E2E test cases using newman.
- Building HTML Report.
- Creating Jenkins job and Run E2E test cases in Jenkins.

## Technologies Used

- [JSON Server](https://github.com/typicode/json-server)
- [JSON Server Auth](https://www.npmjs.com/package/json-server-auth)
- [newman](https://www.npmjs.com/package/newman)
- [newman-reporter-htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra)
- [Jenkins](https://www.jenkins.io/)

## Directory Structure

The repository is organized as follows:
- `newman/`: The directory where HTML Reports are located.
  - `HTML_Report.html`:  This HTML file provides a detailed overview of the test execution results.
- `db.json`: The in-memory data source for this JSON Server application, defining the structure and content of all API endpoints.
- `Project.postman_collection.json`: This file contains a collection of API requests, organized and grouped for testing the JSON Server API. It is used to perform various API tests.
- `Project - Newman.postman_collection.json`: This file contains a collection of API requests, organized and grouped for testing the API through newman.
- `Production.postman_environment.json`: This file stores the environment-specific variables and configurations used for the production testing environment.
- `locally.postman_environment.json`: This file stores the environment-specific variables and configurations used for the local testing environment. This is the environment selected to test the API using newman.
- `QAcart Courses.postman_environment.json`: This file stores the environment-specific variables and configurations used for testing the API through a Postman Mock Server.


## Getting Started

1. Install Postman: [https://www.postman.com/downloads/](https://www.postman.com/downloads/)
2. Import Collections:
    - Download the entire repository or specific files.
    - In Postman, open `"File"` -> `"Import"` -> `"Select Files"` and choose the downloaded files.
3. Configure Environments:
    - Choose the appropriate environment file for your testing environment (e.g., "locally.postman_environment.json").
    - Go to `"File"` -> `"Import"` -> `"Select Files"` and select the chosen file.
4. Run Tests:
    - Within the collection, you can run individual requests or the entire collection.
    - For detailed instructions on test execution, refer to the QAcart course materials.

## Usage

You can go ahead and explore my collections and environments. Feel free to use these collections as reference, study materials, or review materials to enhance your understanding of Postman.

## Contributions

Contributions to this repository are welcome. If you have alternative code implementations, suggestions for improvements please consider submitting a pull request. If you encounter any issues with my implementation or have additional insights to share, please open an issue.

## Disclaimer
> This is not the official implementation.
