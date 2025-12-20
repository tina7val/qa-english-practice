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
