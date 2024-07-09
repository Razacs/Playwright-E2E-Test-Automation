**limehome Solution**
-----------------------------

This repository have solutions of Limehome challenge of Frontend and Backend Task. Below have all details regarding Solutions and execution flow.

**Folder Structure**
--------------------------------
There are 2 folder Structures:

1) Frontned --> That contains all UI Automation based on playwright & Typescript. Tests are executed on multilple browser like chrome, firefox and webkit.
   FrontEnd Task Detail & Folders:
   **Pages** folder contains all the pages of automation
   **tests** folder contains all tests of automation
   **test-results** contains all reports of execution

![image](https://github.com/Razacs/LimeHomeSolution/assets/32739941/c3c013b7-88a2-4484-890c-74929c2e927d)

Execution of Frontend Task:
---------------------------------
**Steps to Follow**

1) cd limehome/Frontend and run yarn install
2) run yarn playwright install
3) for running test  run (yarn test)
**Execution Report:**

![image](https://github.com/Razacs/LimeHomeSolution/assets/32739941/9fe18331-cee7-4e9d-b0c6-25962d2d7b21)

---------------------------------------------
Second Folder is backend:
Backend ---> That contains all backend API tests, tests are written in Playwright & Typescript.
Backend Task details & Folder structure:
**tests** folder has all the tests.
**html-reports** folder has all execution reports
**yarn** file package is for execution

![image](https://github.com/Razacs/LimeHomeSolution/assets/32739941/ad84a3b0-2f7d-40ec-a525-2d2690af02d3)

**Execution of Backend Task:**
------------------------------------
**Steps to follow:**

cd limehome/Frontend and run yarn install
run yarn playwright install
for running test  run (yarn test)

--> The tests are run using 4 parallel workers by default. You can change the workers by running tests using yarn test --workers=n

![image](https://github.com/Razacs/LimeHomeSolution/assets/32739941/42c7ef8e-08b6-4dea-b370-1c4cb5de79db)


Shoping Test Scenario.pdf---> has all test scenarios detail including positive and negative
Test Plan & Test Strategy.pdf--> has all the approach of the solution

Verification Flow Information
------------------------------------------------------------------
This specific test suite, Property Details and Units Verification, focuses on verifying the correctness and completeness of property details fetched from the backend. It covers the following aspects:

Basic Information Matching: Ensures that the basic details of a property, such as name, street, city, and country, match the expected values.
Defined Check-In/Out Times and Amenities: Verifies that properties have defined check-in/check-out times, parking details, and house rules.
Image URL Accessibility: Checks that all property image URLs are accessible and return a 200 status code.
Unit Spaces and Amenities: Checks that Unit spaces comes along proper information, spaces and amenities.


Let me know if you need further infromation from my side, Thanks!
