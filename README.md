# 10 Object-Oriented Programming: Team Profile Generator

# Task

I have built a Node.js command-line application that takes in information about employees on a software engineering team, then generates an HTML webpage that displays summaries for each person. We have tested the code to enssure maintainablity. A test has been written for every part of the code to ensure it passes.

Because this application is not be deployed, a link is provided demonstrating its functionality and all of the tests passing. 

https://drive.google.com/file/d/1mYeqWvdE7EFnyvnGLHp35rtXb5aUGmYh/view
https://drive.google.com/file/d/1TD4pHU1x8fyA9f7XXD5Ts0yCc5Op7lnW/view
https://github.com/mollygove/WK10HW-TeamProfileGen
https://drive.google.com/file/d/1fAJlG1cuDigPAVWHFmK_NW9xe0mFhRIz/view


# User Story

When the user runs the application they are prompted with a series of questions allowing them to enter their employees information. Once satisfied with their entries, an HTML page containing detailed card for each is user is automatically generated.

# Acceptance Criteria

- GIVEN a command-line application that accepts user input
- WHEN I am prompted for my team members and their information
- THEN an HTML file is generated that displays a formatted team roster based on user input
- WHEN I click on an email address in the HTML
- THEN my default email program opens and populates the TO field of the email with the address
- WHEN I click on the GitHub username
- THEN that GitHub profile opens in a new tab
- WHEN I start the application
- THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
- WHEN I enter the team manager’s name, employee ID, email address, and office number
- THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
- WHEN I select the engineer option
- THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
- WHEN I select the intern option
- THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
- WHEN I decide to finish building my team
- THEN I exit the application, and the HTML is generated

### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following:

  * Uses the [Inquirer package](https://www.npmjs.com/package/inquirer).

  * Uses the [Jest package](https://www.npmjs.com/package/jest) for a suite of unit tests.

## Review

![Landing Page](./dist/Landing%20Page.JPG)
