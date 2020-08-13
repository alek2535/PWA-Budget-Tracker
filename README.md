# PWA-Budget-Tracker
Week-18 HW

![License Badge](https://img.shields.io/badge/license-MIT-blue)

## Description

This application is a Budget Tracker application that can be used and downloaded as a PWA (Progressive Web Application) for offline access and functionality.

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## Table of Contents

  * [User-Story](#user-story)
  * [Acceptance-Criteria](#acceptance-criteria)
  * [Deployed Application](#deployed-application)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)

## User Story

```
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```

## Acceptance Criteria

```
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.
```

## Deployed Application

Here is the URL for the deployed [Offline PWA Budget Tracker Application](https://pure-taiga-24715.herokuapp.com/) on Heroku.


## Installation

```
1. Go to https://github.com/alek2535/PWA-Budget-Tracker

2. Fork the branch and then click on clone or download

3. Paste copied link after `git clone` into your bash console in your desired directory

4. You should now have access to the repository
```

Since there is a `package.json`, you will need to run `npm install`.

Once you have the dependancies installed run the command:

```
`npm start`
```

Make sure you have MongoDB running in the background.

## Usage

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

Technologies Used:

* JavaScript
* Node.js
* Express
* Morgan
* MongoDB
* Mongoose
* Compression
* PWA (Progressive Web Application)

## Contributing

Use the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/code_of_conduct.md) when contributing and making pull requests.

For major changes, please create an issue before any changes to discuss them.


## License

[MIT License](./LICENSE)

Copyright (c) 2020 Alek Valencia

## Project Status

This project meets the requirements in the Acceptance Criteria. Any additional changes will be for better performance and additional functionality.

## Tests

There are currently no tests for this project.

## Questions

GitHub profile: [alek2535](https://github.com/alek2535)

Email: alekvalencia2535@gmail.com

If you have any questions about the project you can reach me at the above email.