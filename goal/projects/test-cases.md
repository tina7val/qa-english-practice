# Test Cases for Login Page

## Test Case 1 — Valid Credentials
**Preconditions:**  
User is on the login page

**Steps:**
1. Enter email: test@example.com  
2. Enter password: Test1234  
3. Click “Login”

**Expected Result:**  
User is redirected to dashboard

---

## Test Case 2 — Empty Email
**Preconditions:**  
User is on the login page

**Steps:**
1. Leave email empty  
2. Enter password  
3. Click “Login”

**Expected Result:**  
Error message: “Email required”


## Test Case 3 — Login with invalid password
**Preconditions:** User is on the login page  
**Steps:**
1. Enter valid email
2. Enter invalid password
3. Click Login  
**Expected Result:** Error message is displayed

---
## Test Case 4 — Empty password field
**Preconditions:** User is on the login page  
**Steps:**
1. Enter email
2. Leave password empty
3. Click Login  
**Expected Result:** Error message “Password is required”

---

## Test Case 5 — Both fields empty
**Preconditions:** User is on the login page  
**Steps:**
1. Leave email empty
2. Leave password empty
3. Click Login  
**Expected Result:** Validation errors shown

---

## Test Case 6 — Email format validation
**Preconditions:** User is on the login page  
**Steps:**
1. Enter invalid email format
2. Enter password
3. Click Login  
**Expected Result:** Email format error displayed

---

## Test Case 7 — Password masking
**Preconditions:** User is on the login page  
**Steps:**
1. Type password  
**Expected Result:** Password characters are hidden

---

## Test Case 8 — Login button availability
**Preconditions:** User is on the login page  
**Steps:**
1. Observe Login button  
**Expected Result:** Button is visible and clickable

---

## Test Case 9 — Case sensitivity check
**Preconditions:** User is on the login page  
**Steps:**
1. Enter email with uppercase letters
2. Enter correct password
3. Click Login  
**Expected Result:** Login successful

---

## Test Case 10 — Page refresh
**Preconditions:** User is on the login page  
**Steps:**
1. Enter email and password
2. Refresh the page  
**Expected Result:** Fields are cleared
