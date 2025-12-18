# Defect Reports – SauceDemo

This document contains defect reports identified during manual testing of the SauceDemo web application. All defects are documented following the defined Defect Management template.

---

## Defect ID: BUG-INV-001

### Title
Inventory page displays identical product images for all items when logged in as problem_user

### Description
All products on the Inventory page display the same image when logging in with `problem_user`, which may confuse users and affect product identification.

### Steps to Reproduce
1. Open https://www.saucedemo.com/
2. Login with the following credentials:
   - Username: `problem_user`
   - Password: `secret_sauce`
3. Navigate to the Inventory page

### Expected Result
Each product should display its own correct image corresponding to the product.

### Actual Result
All products display the same image instead of their respective images, while product names, descriptions, prices, and Add to Cart buttons are displayed correctly.

### Severity and Priority
- Severity: Major
- Priority: Medium

### Status
Open

---

## Defect ID: BUG-CART-001

### Title
Remove button does not remove product from cart for problem_user

### Description
The Remove button does not function correctly for `problem_user`, preventing users from removing items from the cart.

### Steps to Reproduce
1. Login with username `problem_user` and password `secret_sauce`
2. Add any product to the cart
3. Click the Remove button

### Expected Result
The selected product should be removed from the cart and the cart badge count should decrease accordingly.

### Actual Result
Clicking the Remove button has no effect. The product remains in the cart and the cart badge count does not decrease.

### Severity and Priority
- Severity: Major
- Priority: High

### Status
Open

---

## Defect ID: BUG-CHECKOUT-001

### Title
Unable to enter text into Last Name field on Checkout Information page

### Description
The Last Name input field cannot be filled during checkout, preventing users from completing the checkout process.

### Steps to Reproduce
1. Login with username `problem_user` and password `secret_sauce`
2. Add a product to the cart
3. Proceed to Checkout
4. Click on the Last Name input field and type any text

### Expected Result
User should be able to enter text into the Last Name field and proceed to the Checkout Overview page.

### Actual Result
Typing in the Last Name field moves the input focus to the First Name field, leaving the Last Name field empty. As a result, the user cannot proceed to the Checkout Overview page.

### Severity and Priority
- Severity: Critical
- Priority: High

### Status
Open

---

## Defect ID: BUG-UI-001

### Title
Cursor does not change to pointer when hovering over Cart icon

### Description
The Cart icon does not provide proper visual feedback when hovered, which may reduce usability.

### Steps to Reproduce
1. Login with any valid user
2. Navigate to the Inventory page
3. Hover the mouse cursor over the Cart icon

### Expected Result
Cursor should change to a pointer to indicate that the Cart icon is clickable.

### Actual Result
Cursor remains in the default state and does not change to a pointer when hovering over the Cart icon.

### Severity and Priority
- Severity: Minor
- Priority: Low

### Status
Open

---

## Defect ID: BUG-UI-002

### Title
Sort dropdown icon does not change orientation when expanded

### Description
The sort dropdown icon does not visually indicate its expanded or active state, which may confuse users.

### Steps to Reproduce
1. Login with any valid user
2. Navigate to the Inventory page
3. Observe the default orientation of the sort dropdown icon
4. Click the sort dropdown

### Expected Result
The sort dropdown icon should change orientation to indicate an active or expanded state.

### Actual Result
The sort dropdown icon does not change orientation and remains in the same direction after being clicked.

### Severity and Priority
- Severity: Minor
- Priority: Low

### Status
Open

