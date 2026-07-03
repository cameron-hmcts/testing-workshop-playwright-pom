# Testing workshop in Playwright.ts - POM repository

This is your starting repository for the workshop!
Here is the website you will be testing https://www.gov.uk/calculate-your-holiday-entitlement

### Pre-requisites

Homebrew - https://brew.sh/

Yarn - `brew install yarn`

Node - `brew install node`

### Setting up the suite

Run these commands first:

`yarn install`

`yarn playwright install`

### To run the tests

`yarn test` will run all tests in a Chromium browser in headed mode

`yarn example_test` will run the example test in a Chromium browser in headed mode

`yarn your_test` will run your test file in a Chromium browser in headed mode

`yarn playwright test` will run your tests in all browsers

You can create new scripts in the package.json file