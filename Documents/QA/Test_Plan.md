# Test Plan

## Table of Contents

<details>
<summary> Click to expand</summary>

- [Test Plan](#test-plan)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Test Environment](#test-environment)
  - [Scope of Testing](#scope-of-testing)
    - [In-Scope Testing](#in-scope-testing)
      - [Functional Testing](#functional-testing)
      - [Non-Functional Testing](#non-functional-testing)
    - [Out-of-Scope Testing](#out-of-scope-testing)
  - [Test Objectives](#test-objectives)
  - [Test Strategy](#test-strategy)
  - [Test Cases](#test-cases)

</details>

## Introduction

This document outlines the test plan for the Bubble project. The goal of this test plan is to ensure that the Bubble project meets its requirements and functions as expected, while also identifying any potential issues or bugs. The test plan will cover various aspects of the project, including functionality, performance, security, and usability.

## Test Environment

The test environment for the Bubble project will consist of only one component: the Bubble project itself. As Bubble is a web-based application, the test environment will be set up on a our computer directly. Tests will mainly be visual and human-based, as there are no automated tests available for the Bubble project. The test environment will be configured to simulate real-world usage scenarios and include various simulated devices to ensure compatibility and responsiveness across different platforms.

## Scope of Testing

The scope of testing of this project encompasses all key requirements pointed out by the client and mentionned in both functional and technical specifications. It will ensure the correctness of the application and its compliance with the specifications.

### In-Scope Testing

#### Functional Testing

Functional testing will be performed to ensure that the application meets its functional requirements. This includes testing the following features:

- Navigation between pages (home, profile, settings, etc.)
- Display and update of user profile data
- Integration with third-party services or APIs if applicable
- Responsive design across various screen sizes (mobile, tablet, desktop)

#### Non-Functional Testing

- Usability testing to ensure intuitive user experience
- Performance testing for acceptable load times and responsiveness
- Accessibility testing to verify compliance with WCAG guidelines

> [!NOTE]
> The WCAG (Web Content Accessibility Guidelines) is a set of guidelines for making web content more accessible to people with disabilities. It covers a wide range of recommendations for making web content more accessible, including text alternatives for non-text content, captions for audio and video content, and ensuring that all functionality is available from a keyboard.

### Out-of-Scope Testing

The following elements are outside the scope of this test plan:

- Automated testing (unit, integration, or end-to-end automation)
- Testing of infrastructure or server-side hosting environment
- Load testing at extreme traffic volumes (e.g., stress testing beyond expected usage)
- Penetration testing or in-depth cybersecurity audits
- Localization and internationalization testing (non-English language support)
- Testing on legacy browsers no longer supported (e.g., Internet Explorer)
- Testing of non-core modules or experimental features not required by the client

## Test Objectives

The objectives of the testing process is to rigorously evaluate that our MVP meets the requirements and objectives mentionned during the project kickoff, but also in the specifications.
Here's the list of objectives we will be testing:

- Verify that the application meets the functional requirements outlined in the specifications
- Ensure that the application is user-friendly and provides a positive user experience
- Validate that the application performs well under expected usage conditions
- Confirm that the application is accessible to users with disabilities
- Identify and document any defects or issues found during testing
- Provide feedback to the development team for continuous improvement
- Ensure that the application is ready for deployment and meets the client's expectations
- Validate that the application is compatible with various devices and screen sizes

## Test Strategy

The test strategy for the Bubble project will involve a combination of manual testing and exploratory testing. Given the nature of the project, automated testing is not feasible at this stage. The testing process will be divided into the following phases:

1. **Test Planning**: Define the scope, objectives, and strategy for testing.
2. **Test Design**: Create test cases and scenarios based on the requirements and specifications.
3. **Test Execution**: Execute the test cases and document the results.
4. **Defect Reporting**: Log any defects or issues found during testing and communicate them to the development team.
5. **Test Closure**: Evaluate the testing process, document lessons learned, and provide a final report to stakeholders.
6. **Regression Testing**: If any defects are fixed, perform regression testing to ensure that the fixes do not introduce new issues.
7. **User Acceptance Testing (UAT)**: Involve the client and various people that might be future users in testing to validate that the application meets their expectations and requirements.

## Test Cases

The test cases will be derived from the requirements and specifications of the Bubble project. Each test case will include the following information:

- Test Case ID
- Test Case Description
- Pre-conditions
- Test Steps
- Expected Results
- Actual Results
- Status (Pass/Fail)
- Comments/Notes

The test cases will be organized into categories based on the features being tested (development, design, etc.). Each test case will be executed manually, and the results will be documented in a test management tool or spreadsheet. The test cases will be reviewed and approved by the project manager and the tech lead before execution.
