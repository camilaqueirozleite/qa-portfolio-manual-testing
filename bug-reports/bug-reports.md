# Bug Reports - SauceDemo

## Project: SauceDemo QA Manual Testing

---

## 🐞 BUG-001 - Missing clear error message on failed login

### Title:
Login error message is not clear for invalid credentials

### Environment:
- Browser: Chrome
- OS: Windows / Mac
- URL: https://www.saucedemo.com

### Steps to Reproduce:
1. Open login page
2. Enter valid username: standard_user
3. Enter invalid password: 123456
4. Click Login button

### Expected Result:
A clear and user-friendly error message should appear, such as:
"Username and password do not match any user in this service."

### Actual Result:
Generic error message is displayed without clear guidance.

### Severity:
Medium

### Priority:
High

---

## 🐞 BUG-002 - Cart state not preserved after page refresh

### Steps to Reproduce:
1. Login successfully
2. Add a product to cart
3. Refresh the page

### Expected Result:
Cart should retain previously added items after refresh.

### Actual Result:
Cart becomes empty after page refresh.

### Severity:
High

### Priority:
High

---

## 🐞 BUG-003 - UI alignment issue on product page

### Steps to Reproduce:
1. Login successfully
2. Navigate to product listing page

### Expected Result:
All UI elements should be properly aligned and responsive.

### Actual Result:
Some buttons and text appear misaligned depending on screen size.

### Severity:
Low

### Priority:
Low

---

## 🧠 Notes:
All issues were identified during manual exploratory testing of core user flows.
