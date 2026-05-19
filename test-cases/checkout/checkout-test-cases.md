# Checkout Test Cases - SauceDemo

## Feature: Checkout Process

---

## TC-001 - Successful checkout flow

### Objective:
Verify that user can complete checkout successfully.

### Precondition:
User is logged in and has at least one product in the cart.

### Steps:
1. Go to cart
2. Click "Checkout"
3. Enter valid information:
   - First Name: Camila   
   - Last Name: Leite
   - Postal Code: 4000
4. Click "Continue"
5. Click "Finish"

### Expected Result:
Order should be completed successfully and confirmation message should be displayed.

---

## TC-002 - Checkout with empty fields

### Objective:
Verify validation when user submits empty checkout form.

### Steps:
1. Go to checkout page
2. Leave all fields empty
3. Click "Continue"

### Expected Result:
System should display error message for required fields.

---

## TC-003 - Invalid postal code

### Objective:
Verify system behavior with invalid postal code.

### Steps:
1. Enter valid first and last name
2. Enter invalid postal code (e.g. ABC123)
3. Click "Continue"

### Expected Result:
System should reject invalid postal code format.

---

## TC-004 - Cancel checkout process

### Objective:
Verify user can cancel checkout process.

### Steps:
1. Start checkout process
2. Click "Cancel"

### Expected Result:
User should be redirected back to cart page without completing order.

---

## TC-005 - Checkout without cart items

### Objective:
Verify system behavior when trying to checkout with empty cart.

### Steps:
1. Open cart with no products
2. Click "Checkout"

### Expected Result:
System should prevent checkout and show appropriate message.

---

## TC-006 - UI validation during checkout

### Objective:
Verify checkout form UI elements.

### Steps:
1. Open checkout page

### Expected Result:
- All input fields visible
- Buttons functional
- Layout properly aligned
