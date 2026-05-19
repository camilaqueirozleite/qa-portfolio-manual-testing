# Login Test Cases - SauceDemo

## Feature: Login

---

## TC-001 - Valid Login

### Objective:
Verify that user can login successfully with valid credentials.

### Precondition:
User is on the login page: https://www.saucedemo.com

### Test Data:
- Username: standard_user
- Password: secret_sauce

### Steps:
1. Enter valid username
2. Enter valid password
3. Click Login button

### Expected Result:
User should be redirected to the Products page.

---

## TC-002 - Invalid Password

### Objective:
Verify system behavior when password is incorrect.

### Steps:
1. Enter valid username: standard_user
2. Enter invalid password: 123456
3. Click Login button

### Expected Result:
Error message should be displayed: "Username and password do not match"

---

## TC-003 - Empty Fields

### Objective:
Verify validation when login fields are empty.

### Steps:
1. Leave username empty
2. Leave password empty
3. Click Login

### Expected Result:
Error message should be displayed for missing credentials.

---

## TC-004 - Locked User

### Objective:
Verify login behavior for locked user.

### Test Data:
- Username: locked_out_user
- Password: secret_sauce

### Steps:
1. Enter locked user credentials
2. Click Login

### Expected Result:
User should not be able to login and error message should appear.

---

## TC-005 - UI Validation

### Objective:
Verify login page UI elements.

### Steps:
1. Open login page

### Expected Result:
- Username field visible
- Password field visible
- Login button visible and clickable
