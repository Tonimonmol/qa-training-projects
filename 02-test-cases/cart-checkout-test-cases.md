# Cart & Checkout Test Cases – SauceDemo

## TC-004: Add product to cart
**Precondition:** User is logged in (Standard User)  
**Steps:**
1. Login to the application
2. Click "Add to cart" on any product  
**Expected Result:** Product is added to the cart

---

## TC-005: View product in cart
**Precondition:** Product added to cart  
**Steps:**
1. Click on cart icon  
**Expected Result:** Product is displayed in cart

---

## TC-006: Remove product from cart
**Precondition:** Product added to cart  
**Steps:**
1. Click "Remove" on product  
**Expected Result:** Product is removed from cart

---

## TC-007: Start checkout process
**Precondition:** Product added to cart  
**Steps:**
1. Click Checkout  
**Expected Result:** Checkout information page is displayed

---

## TC-008: Complete checkout with valid data
**Precondition:** User is on checkout information page  
**Steps:**
1. Enter First Name
2. Enter Last Name
3. Enter Postal Code
4. Click Continue  
**Expected Result:** Checkout overview page is displayed

---

## TC-009: Checkout with empty fields
**Precondition:** User is on checkout information page  
**Steps:**
1. Leave all fields empty
2. Click Continue  
**Expected Result:** Validation error is displayed
