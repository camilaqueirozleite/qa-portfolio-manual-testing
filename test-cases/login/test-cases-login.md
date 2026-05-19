Login Test Cases - SauceDemo
Feature: Login
TC-001 - Valid Login
Objective:
Verify that user can login with valid credentials.

Precondition:
User is on login page: https://www.saucedemo.com

Steps:
Enter valid username: standard_user
Enter valid password: secret_sauce
Click on Login button
Expected Result:
User is redirected to the Products page.

TC-002 - Invalid Password
Objective:
Verify login fails with wrong password.

Steps:
Enter valid username: standard_user
Enter invalid password: 123456
Click Login
Expected Result:
Error message is displayed.

TC-003 - Empty Fields
Objective:
Verify validation when fields are empty.

Steps:
Leave username empty
Leave password empty
Click Login
Expected Result:
Error message is displayed indicating missing fields.
