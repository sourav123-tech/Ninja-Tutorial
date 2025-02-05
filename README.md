# Ninja-Tutorial
This repository contains manual tests for a web application . The project focuses on testing two main features:
1. Homepage Design and Navigation
2. Newsletter Subscription

## Table of Contents
- [Features Tested](#features-tested)
- [Test Plan](#test-plan)
- [Test Scenarios](#test-scenarios)
- [Test Cases](#test-cases)
- [Bug Reports](#bug-reports)
- [Summary Report](#summary-report)
- [Getting Started](#getting-started)
- [Running the Tests](#running-the-tests)
- [Contributing](#contributing)
- [License](#license)

## Features Tested

### 1. Homepage Design and Navigation
- **Objective**: Verify that the homepage design is consistent and that navigation links are functional.
- **Key Checks**:
  - Layout and design elements are displayed correctly.
  - Navigation links redirect to the correct pages.
  - Responsive design on different screen sizes.

### 2. Newsletter Subscription
- **Objective**: Ensure that the newsletter subscription feature works as expected.
- **Key Checks**:
  - User can subscribe with a valid email address.
  - Error messages are displayed for invalid email addresses.
  - Success message is shown upon successful subscription.

## Test Plan

### Scope
- **In Scope**: Homepage design, navigation, and newsletter subscription functionality.
- **Out of Scope**: Other features of the web application not related to the homepage or newsletter.

### Test Environment
- **Browser**: Chrome, Firefox and safari
- **Operating System**: Windows 10, macOS

### Test Strategy
- **Manual Testing**: Initial exploratory testing.

## Test Scenarios

### Homepage Design and Navigation
1. Verify that the homepage loads correctly.
2. Verify that all navigation links are functional.
3. Verify that the layout is responsive on different screen sizes.

### Newsletter Subscription
1. Verify that a user can subscribe with a valid email address.
2. Verify that an error message is displayed for an invalid email address.
3. Verify that a success message is shown upon successful subscription.

## Test Cases

### Homepage Design and Navigation
- **TC001**: Verify homepage layout.
- **TC002**: Verify navigation links.
- **TC003**: Verify responsive design.

### Newsletter Subscription
- **TC004**: Verify valid email subscription.
- **TC005**: Verify invalid email error message.
- **TC006**: Verify subscription success message.

## Bug Reports

### Bug 001: Navigation Link Broken
- **Description**: The "About Us" link on the homepage redirects to a 404 page.
- **Severity**: High
- **Steps to Reproduce**:
  1. Navigate to the homepage.
  2. Click on the "About Us" link.
- **Expected Result**: Redirect to the "About Us" page.
- **Actual Result**: 404 error page.

### Bug 002: Newsletter Subscription Error
- **Description**: No error message is displayed when an invalid email is entered.
- **Severity**: Medium
- **Steps to Reproduce**:
  1. Navigate to the newsletter subscription section.
  2. Enter an invalid email (e.g., "invalid-email").
  3. Click the subscribe button.
- **Expected Result**: Error message "Please enter a valid email address."
- **Actual Result**: No error message is displayed.

## Summary Report

### Test Execution Summary
- **Total Test Cases**: 39
- **Passed**: 27
- **Failed**: 12
- **Success Rate**: 66.67%

### Key Findings
- Two critical bugs were identified:
  1. Broken navigation link.
  2. Missing error message for invalid email subscription.

### Recommendations
- Fix the broken navigation link.
- Implement error message validation for the newsletter subscription feature.
