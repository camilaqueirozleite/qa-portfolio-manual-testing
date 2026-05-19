# Cart Test Cases - SauceDemo

## Feature: Shopping Cart

---

## TC-001 - Add product to cart

### Objective:
Verify that a product can be added to the cart successfully.

### Precondition:
User is logged in and on the products page.

### Steps:
1. Click on a product
2. Click "Add to cart" button
3. Open cart icon

### Expected Result:
Selected product should appear in the cart with correct details.

---

## TC-002 - Remove product from cart

### Objective:
Verify that a product can be removed from the cart.

### Steps:
1. Add product to cart
2. Open cart page
3. Click "Remove" button

### Expected Result:
Product should be removed from cart successfully.

---

## TC-003 - Cart persistence after navigation

### Objective:
Verify that cart data is maintained when navigating between pages.

### Steps:
1. Add product to cart
2. Navigate back to products page
3. Return to cart

### Expected Result:
Cart should still contain the selected product.

---

## TC-004 - Cart persistence after refresh

### Objective:
Verify cart state after page refresh.

### Steps:
1. Add product to cart
2. Refresh browser page

### Expected Result:
Cart should still contain the product after refresh.

---

## TC-005 - Add multiple products to cart

### Objective:
Verify that multiple products can be added correctly.

### Steps:
1. Add Product A
2. Add Product B
3. Open cart

### Expected Result:
Both products should appear in cart with correct quantities.

---

## TC-006 - Remove all items from cart

### Objective:
Verify cart becomes empty after removing all items.

### Steps:
1. Add multiple products
2. Remove all items

### Expected Result:
Cart should display empty state.

---

## 🧠 Notes:
Cart functionality is critical for e-commerce applications and requires validation of state persistence, data integrity and user experience.
