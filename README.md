QA Project – Test Design Using Equivalence Partitioning

Project Description

This project documents the Quality Assurance (QA) test design process carried out during the second testing sprint. The focus of this project was to validate the "Add Driver’s License" form in an application by applying the Equivalence Partitioning testing technique.
The objective was to design efficient test cases by dividing input data into valid and invalid equivalence classes, reducing the number of tests required while still ensuring adequate coverage of the system’s behavior.

Testing Objectives

Validate the correct behavior of the driver’s license registration form.
Identify how the system handles valid and invalid input data.
Apply equivalence partitioning to optimize the number of test cases.
Ensure that form validations and data constraints work correctly.

Testing Scope

The testing focused on the form used to add a driver’s license, verifying how the application processes different types of input. The main fields tested included:

Driver’s Name
Driver’s license number
Expiration date
Other required form inputs and validation rules

The tests checked whether the system:

Accepts valid input values.
Rejects invalid values with proper validation messages.
Prevents incorrect or incomplete data from being submitted.
Testing Technique Used
Equivalence Partitioning
Equivalence Partitioning is a black-box testing technique used to divide input data into groups (equivalence classes) that should be processed similarly by the system.

Each class represents a set of values where:

Valid classes contain acceptable input values.
Invalid classes contain values that should trigger validation errors.
Instead of testing every possible input, one representative value from each class is selected to design test cases.

This approach helps to:

Reduce redundant testing.
Increase efficiency.
Maintain good test coverage.

Test Case Design

Based on the defined equivalence classes, a set of structured test cases was created including:

Test Case ID
Test Scenario
Input Data
Steps to Execute
Expected Result
Test Status

These test cases ensure that both valid and invalid inputs are properly tested.

Example Validation Scenarios

The test cases cover situations such as:

Entering a valid driver’s name.
Leaving required fields empty.
Entering an invalid driver’s license number format.
Submitting the form with expired or incorrect dates.
Validating error messages and system behavior.

Project Structure

/qa-form-validation-testing
│
├── Equivalence Classes
│   Definition of valid and invalid input groups
│
├── Test Cases
│── Test scenarios designed based on the equivalence classes

QA Process Applied

Analysis of the form requirements.
Identification of input fields and validation rules.
Definition of equivalence classes (valid and invalid).
Test case design based on representative values.
Documentation of the testing scenarios.

Results

The application of Equivalence Partitioning allowed the creation of optimized test cases while maintaining effective coverage of the form’s validation logic.
This approach helped to ensure that the driver’s license form correctly processes user input and handles validation errors properly.
