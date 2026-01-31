# Login Test Cases – SauceDemo

## TC-001: Valid login with correct credentials
**Precondition:** User is on login page  
**Steps:**
1. Enter valid username
2. Enter valid password
3. Click Login button  
**Expected Result:** User is redirected to products page

---

## TC-002: Login with invalid password
**Precondition:** User is on login page  
**Steps:**
1. Enter valid username
2. Enter invalid password
3. Click Login button  
**Expected Result:** Error message is displayed

---

## TC-003: Login with empty fields
**Precondition:** User is on login page  
**Steps:**
1. Leave username empty
2. Leave password empty
3. Click Login button  
**Expected Result:** Validation error is displayed
