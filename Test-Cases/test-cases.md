# Test Cases – Custodian Application

## 1. Objective
Document functional test scenarios for the Custodian desktop application. These test cases demonstrate manual testing concepts and automation testing preparation using SikuliX and Jython.

## 2. Application Module
- Module: Customer Master
- Application Type: Desktop Application
- Automation Tool: SikuliX
- Scripting Language: Python (Jython)
- Test Data: CSV

## 3. Test Scenarios

| Test Case ID | Test Scenario | Test Type | Expected Result |
|---|---|---|---|
| TC001 | Launch application | Functional | Application opens successfully |
| TC002 | Open Customer Master form | UI Testing | Customer Master form is displayed |
| TC003 | Enter valid customer details | Positive | All valid inputs are accepted |
| TC004 | Leave mandatory fields empty | Negative | Appropriate validation message appears |
| TC005 | Enter invalid customer details | Negative | Invalid inputs are rejected |
| TC006 | Enter duplicate customer details | Negative | Duplicate record validation is displayed, if applicable |
| TC007 | Submit valid customer details | Functional | Customer record is saved successfully |
| TC008 | Cancel customer entry | Functional | Entry is cancelled without saving |
| TC009 | Verify saved customer details | Data Validation | Saved details match the entered test data |
| TC010 | Verify application response to invalid input | UI Validation | Application handles invalid input without unexpected failure |

## 4. Preconditions
- Application is available in the test environment.
- Tester has valid login credentials.
- Customer Master module is accessible.
- Sample test data is available.
- Required application images are available for SikuliX automation.

## 5. Testing Types
- Functional Testing
- Positive Testing
- Negative Testing
- UI Validation
- Data-Driven Testing
- Database Validation

## 6. Execution Status

| Status | Description |
|---|---|
| Not Executed | Test execution is pending |
| Pass | Actual result matches expected result |
| Fail | Actual result differs from expected result |
| Blocked | Test cannot be executed due to an issue |

