# Test Cases

This section demonstrates my approach to designing clear, structured, and risk-based test cases.

## Testing Areas

- Functional Testing
- Positive & Negative Testing
- Boundary Value Testing
- Validation Testing
- Business Rule Validation
- User Role & Permission Testing
- Integration Testing
- Regression Testing

## Test Case Structure

| Field | Description |
|---|---|
| Test Case ID | Unique identifier |
| Test Scenario | What is being validated |
| Preconditions | Required conditions before execution |
| Test Steps | Steps required to execute the test |
| Expected Result | Expected system behavior |
| Priority | Business/testing priority |
| Test Type | Functional, Negative, Regression, etc. |

## Example

| Test Case ID | TC-LOGIN-001 |
|---|---|
| Scenario | Login with valid credentials |
| Preconditions | Registered user exists |
| Steps | 1. Open login page<br>2. Enter valid email<br>3. Enter valid password<br>4. Click Login |
| Expected Result | User is successfully logged in and redirected to the dashboard |
| Priority | High |
| Test Type | Functional / Positive |
