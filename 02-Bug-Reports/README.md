# Bug Reports

This section demonstrates my approach to reporting software defects clearly and effectively.

## Bug Report Structure

| Field | Description |
|---|---|
| Bug ID | Unique defect identifier |
| Title | Clear summary of the issue |
| Environment | Application, platform, browser, or device |
| Preconditions | Conditions required before testing |
| Steps to Reproduce | Steps needed to reproduce the issue |
| Actual Result | What actually happened |
| Expected Result | What should have happened |
| Severity | Impact of the defect |
| Priority | Urgency of fixing the defect |
| Status | Current defect status |

## Example Bug Report

### BUG-001 — Login button remains disabled after entering valid credentials

**Environment:** Web Application — Chrome

**Preconditions:**
- Registered user account exists.
- User is on the Login page.

**Steps to Reproduce:**

1. Open the Login page.
2. Enter a valid email address.
3. Enter a valid password.
4. Observe the Login button.

**Actual Result:**

The Login button remains disabled even though valid credentials have been entered.

**Expected Result:**

The Login button should become enabled and allow the user to submit the login request.

**Severity:** High

**Priority:** High

**Status:** Open

### QA Analysis

**Impact:** Users with valid credentials are unable to access the application.

**Suggested Investigation:**

- Validate frontend field validation.
- Check whether the login button state is triggered correctly.
- Validate the authentication API request.
- Review browser console errors.
- Verify behavior across supported browsers.
