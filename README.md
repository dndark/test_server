# Interview Test Server

Welcome to the Points developer take-home assignment.

Your task is to build an app against a small API. [Download the docker image](#Getting-started) onto your computer and run it locally. The instructions for each assignment live at the base of the API routes, as well as in the respective *INSTRUCTIONS.md* files. You may choose one of the following tasks:

* [Autonomous Car](./api/autonomous_car/INSTRUCTIONS.md)
* [Tax Calculator](./api/tax_calculator/INSTRUCTIONS.md)

**Please timebox your solution to one day total.**

## Getting started

```bash
docker pull ptsdocker16/interview-test-server
docker run --init -p 5000:5000 -it ptsdocker16/interview-test-server
```

Navigate to [http://localhost:5000](http://localhost:5000). You should see a brief set of instructions. From there you'll be able to query the above endpoints and do your assignment. If you have any problems or need any sort of clarification, email the Team Lead or Engineering Hiring Manager for assistance.

## Submission Instructions

You can either submit your code as a zip file or send a link to a personal repository. Do not fork or submit pull requests to this repository. Please submit within a week or 2 of receipt of instructions, unless otherwise specified.

Please *do not fork or submit pull requests* to this repository.

Please timebox your solution to one day total.

* Implement your solution using a language agreed upon by your hiring manager.
* Include comments where you feel that they would be helpful.
* Include a README with instructions on how setup, run, and test the application.
* Include unit tests.

**If using JavaScript**

* Create a simple, yet visually appealing and responsive design.
* Target the latest stable version of Google Chrome.

**If using a backend language**

* Implement a simple yet intuitive command line interface OR create a REST api endpoint to display the information in a JSON format.

**Code Formatting**

If using one of the following languages, make sure it adheres to the corresponding style guide:

* JavaScript : Eslint
* Python : PEP8
