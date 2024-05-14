# Manual Testing Project

## Project Description

This project involves detailed manual testing of a web application to identify bugs and improve overall usability. The focus is on creating comprehensive test cases and executing them to ensure the application's functionality meets the specified requirements.

## Tools Used

- **Selenium**: For automated browser testing.
- **JIRA**: For tracking bugs and managing test cases.
- **TestRail**: For managing test cases and test plans.

## Test Cases

1. **Login Functionality**
   - **Description**: Verify that users can log in with valid credentials.
   - **Steps**:
     1. Navigate to the login page.
     2. Enter valid username and password.
     3. Click on the login button.
   - **Expected Result**: User is redirected to the dashboard.

2. **Signup Functionality**
   - **Description**: Verify that new users can sign up successfully.
   - **Steps**:
     1. Navigate to the signup page.
     2. Enter required information.
     3. Click on the signup button.
   - **Expected Result**: User receives a confirmation email and can log in.

## Bug Reports

- **Bug 1**: Login page crashes on invalid input.
  - **Description**: The application crashes when an invalid username is entered.
  - **Steps to Reproduce**:
    1. Navigate to the login page.
    2. Enter an invalid username.
    3. Click on the login button.
  - **Expected Result**: An error message should be displayed.
  - **Actual Result**: The application crashes.
  - **Severity**: High
  - **Status**: Open

## Results

- **Bug Reports**: Detailed bug reports with steps to reproduce and screenshots.
- **Test Cases Executed**: Comprehensive list of executed test cases with results.
