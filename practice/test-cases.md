# Test Cases Practice

This file contains my test case practice while learning Manual QA.

## Login Form

### TC-001 — Login with valid credentials

**Preconditions:**
- User has a registered account.

**Steps:**
1. Open the login page.
2. Enter a valid email.
3. Enter a valid password.
4. Click the "Login" button.

**Expected Result:**
- User is successfully logged in.
- User is redirected to their account page.


### TC-002 — Login with invalid password

**Preconditions:**
- User has a registered account.

**Steps:**
1. Open the login page.
2. Enter a valid email.
3. Enter an invalid password.
4. Click the "Login" button.

**Expected Result:**
- User is not logged in.
- User remains on the login page.
- An error message about incorrect credentials is displayed.


### TC-003 — Login with empty email field

**Preconditions:**
- User has a registered account.

**Steps:**
1. Open the login page.
2. Leave the email field blank.
3. Enter a valid password.
4. Click the "Login" button.

**Expected Result:**
- User is not logged in.
- User remains on the login page.
- A validation message for the required email field is displayed.

- ### TC-004 — Login with empty password field

**Preconditions:**
- User has a registered account.

**Steps:**
1. Open the login page.
2. Enter a valid email.
3. Leave the password field blank.
4. Click the "Login" button.

**Expected Result:**
- User is not logged in.
- User remains on the login page.
- A validation message for the required password field is displayed.
