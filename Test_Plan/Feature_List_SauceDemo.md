# Sauce Demo – Feature List

---

## 1. Home / Login Page
- Username field
- Password field
- Login button
- Credentials information
  - Display accepted username and password

---

## 2. Common Layout Components

### 2.1 Navigation & Header
- Hamburger menu icon
  - Open / Close menu
  - All Items (Inventory)
  - About (redirects to https://saucelabs.com/)
  - Logout
  - Reset App State
- Swag Labs title text
- Cart icon (navigation link)

### 2.2 Footer
- Social media icons
  - Twitter (external link)
  - Facebook (external link)
  - LinkedIn (external link)
- Copyright text
  - © 2025 Sauce Labs. All Rights Reserved.
  - Terms of Service | Privacy Policy

---

## 3. Inventory Page
**URL:** https://www.saucedemo.com/inventory.html

### 3.1 Product Listing
- Products title text
- Product sorting (Filter)
  - Name (A to Z) – default
  - Name (Z to A)
  - Price (Low to High)
  - Price (High to Low)

### 3.2 Product List Layout
- Two-column layout
- Total of 6 products

### 3.3 Product Item Details
- Product image (clickable link)
- Product name (clickable link)
- Product description text
- Product price text
- Add to cart button

---

## 4. Product Detail Page
**URL:** https://www.saucedemo.com/inventory-item.html?id=0

### 4.1 Product Information
- Back to Products button (with back arrow)
- Product image (larger size)
- Product name text
- Product description text
- Product price text
- Add to cart button

### 4.2 Add to Cart Behavior
- Add to cart button changes to **Remove** after click
- Button color changes to red when item is added

---

## 5. Cart Page (Your Cart)
- Quantity (QTY) column
- Description column
- Quantity box (non-editable)
- Product name (clickable link)
- Product description text
- Product price text
- Remove button
- Continue Shopping button (navigates to Inventory page)
- Checkout button

---

## 6. Checkout – Your Information
**URL:** https://www.saucedemo.com/checkout-step-one.html

- First Name input field
- Last Name input field
- Zip / Postal Code input field
- Cancel button (navigates back to Cart page)
- Continue button

---

## 7. Checkout – Overview
**URL:** https://www.saucedemo.com/checkout-step-two.html

### 7.1 Order Details
- Quantity (QTY) column
- Description column
- Quantity box (non-editable)
- Product name text
- Product description text
- Product price text

### 7.2 Payment Information
- SauceCard #31337

### 7.3 Shipping Information
- Free Pony Express Delivery!

### 7.4 Price Summary
- Item total
- Tax
- Total price

- Cancel button (navigates back to Inventory page)
- Finish button (navigates to Checkout Complete page)

---

## 8. Checkout – Complete
**URL:** https://www.saucedemo.com/checkout-complete.html

- Success icon (green checkmark)
- Confirmation message text
  - "Thank you for your order!"
  - "Your order has been dispatched, and will arrive just as fast as the pony can get there!"
- Back Home button (navigates to Inventory page)

---

## 9. Known Issues / Observed Bugs
- Filter icon does not change orientation when a sorting option is selected
- Cursor does not change to pointer when hovering over Cart icon
