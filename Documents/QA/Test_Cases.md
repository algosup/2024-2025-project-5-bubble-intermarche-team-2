# Test Cases

## Purpose

This document outlines the various test cases that will be executed to ensure the functionality and reliability of the system. Each test case includes a description, expected outcome, and actual outcome.

## Criticality Levels

There are three criticality levels for the test cases:

| Criticality Level | Color Code | Description                                                                              |
| ----------------- | ---------- | ---------------------------------------------------------------------------------------- |
| High              | Red        | Critical functionality that must work for the system to be operational.                  |
| Medium            | Yellow     | Important functionality that should work but is not critical for the system's operation. |
| Low               | Green      | Non-critical functionality that is nice to have but not essential.                       |

## Categories

Each test case is categorized into one of the following categories:

| Category      | Description                                                                |
| ------------- | -------------------------------------------------------------------------- |
| Functional    | Tests that verify the system performs its intended functions.              |
| Performance   | Tests that assess the system's performance under various conditions.       |
| Usability     | Tests that check the user interface and user experience.                   |
| Compatibility | Tests that ensure the system works across different platforms and devices. |
| Regression    | Tests that verify that new changes do not break existing functionality.    |
| Integration   | Tests that check the interaction between different system components.      |

## Test Cases List

### Test Case 1: Access to the Application

- **Description**: Verify that users can access the application without issues.
- **Category**: Functional
- **Criticality**: High (🔴)
- **Procedure**:
  1. Scan the QR code to access the application.
  2. Ensure the application loads successfully.
- **Expected Outcome**: The application should load without errors, and the user should be able to navigate to the main interface.
- **Actual Outcome**: Passed

### Test Case 2: Language Selection

- **Description**: Verify that users can select their preferred language.
- **Category**: Usability
- **Criticality**: Medium (🟡)
- **Procedure**:
  1. Access the language selection menu.
  2. Choose a different language from the available options.
- **Expected Outcome**: The application should switch to the selected language without issues.
- **Actual Outcome**: Passed

### Test Case 3: Barcode Scanning

- **Description**: Verify that the barcode scanning functionality works correctly.
- **Category**: Functional
- **Criticality**: Medium (🟡)
- **Procedure**:
  1. Allow the application to access the camera.
  2. CLick on the _Activate the camera_ button.
  3. Scan a valid barcode.
  4. Ensure the scanned data is displayed correctly.
- **Expected Outcome**: The application should successfully scan the barcode and display the correct data.
- **Actual Outcome**: Failed on Android devices due to permission issues. Passed on iOS devices.

### Test Case 4: Matching Products

- **Description**: Verify that the application can match selected products with the wine / cheese / recipe database.
- **Category**: Functional
- **Criticality**: High (🔴)
- **Procedure**:
  1. Access to a product via the barcode scanning or manual search.
  2. Scroll through the product details.
  3. Check the _Wine association_ and _Cheese Association_ sections.
  4. Verify that the product matches with the database entries.
- **Expected Outcome**: The application should display the correct wine and cheese associations for the selected product.
- **Actual Outcome**: Not applicable yet, as the database is not fully populated.

### Test Case 5: Responsive Design

- **Description**: Verify that the application is responsive and works well on different screen sizes.
- **Category**: Usability
- **Criticality**: Medium (🟡)
- **Procedure**:
  1. Access the application on devices with different screen sizes (e.g., mobile, tablet, desktop).
  2. Navigate through the application.
- **Expected Outcome**: The application should display correctly on all devices, with no layout issues.
- **Actual Outcome**: Passed on all tested devices.

### Test Case 6: User Friendly Interface

- **Description**: Verify that the user interface is intuitive and easy to navigate.
- **Category**: Usability
- **Criticality**: Medium (🟡)
- **Procedure**:
  1. Ask people in the street if they are able to help us for 5 minutes of testing.
  2. Observe their interactions with the application.
  3. Collect feedback on usability.
  4. Make adjustments based on feedback.
- **Expected Outcome**: Users should be able to navigate the application without confusion, and feedback should indicate a positive user experience.
- **Actual Outcome**: Feedback was generally positive, with some suggestions for minor improvements in navigation, especially regarding the _Localization_ section.

### Test Case 7: Localization

- **Description**: Verify that the application localize properly the various elements in the supermarket.
- **Category**: Usability
- **Criticality**: Medium (🟡)
- **Procedure**:
  1. Navigate to the _Localization_ section.
  2. Select various elements in the supermarket, such as wine or cheese aisles.
  3. Ensure that the application displays the correct localized information.
- **Expected Outcome**: The application should display the correct localized information for the selected elements.
- **Actual Outcome**: Passed, with some minor issues regarding precision in the localization of certain elements, which will be addressed in future updates.
