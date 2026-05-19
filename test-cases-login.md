# Login Test Cases - SauceDemo

## Feature: Login

---

## TC-001 - Valid Login

### Objective:
Verify that user can login with valid credentials.

### Precondition:
User is on login page: https://www.saucedemo.com

### Steps:
1. Enter valid username: standard_user
2. Enter valid password: secret_sauce
3. Click on Login button

### Expected Result:
User is redirected to the Products page.

---

## TC-002 - Invalid Password

### Objective:
Verify login fails with wrong password.

### Steps:
1. Enter valid username: standard_user
2. Enter invalid password: 123456
3. Click Login

### Expected Result:
Error message is displayed.

---

## TC-003 - Empty Fields

### Objective:
Verify validation when fields are empty.

### Steps:
1. Leave username empty
2. Leave password empty
3. Click Login

### Expected Result:
Error message is displayed indicating missing fields.
