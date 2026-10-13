# Login Page Test Cases

## TC-001: Login with valid credentials
- **Precondition:** User has a registered account.
- **Steps:**
  1. Open the login page.
  2. Enter a valid username.
  3. Enter a valid password.
  4. Click Login.
- **Expected Result:** User logs in successfully and reaches the home page.
- **Status:** Not Executed

## TC-002: Login with an invalid password
- **Steps:**
  1. Open the login page.
  2. Enter a valid username.
  3. Enter an incorrect password.
  4. Click Login.
- **Expected Result:** An appropriate error message appears, and login is denied.
- **Status:** Not Executed

## TC-003: Login with empty fields
- **Steps:**
  1. Open the login page.
  2. Leave the username and password empty.
  3. Click Login.
- **Expected Result:** Validation messages appear, or login is denied.
- **Status:** Not Executed