# Daraz Login Test Cases

## TS01: Login Functionality

---

### ✅ TC01: Login with valid credentials
**Test Data:** valid@gmail.com / CorrectPassword123
**Precondition:** Login page is open

**Steps:**
1. Enter valid email & password
2. Click Login

**Expected Result:**
User logs in successfully

**Actual Result:**
User logged in

**Status:** Pass
**Priority:** High

---

### ❌ TC02: Login with invalid password
**Test Data:** valid@gmail.com / wrongPassword123

**Steps:**
1. Enter valid email & wrong password
2. Click Login

**Expected Result:**
Error message should display

**Actual Result:**
No proper error message

**Status:** Fail
**Bug:** Validation missing
**Priority:** High

---

### ❌ TC03: Login with invalid email
**Test Data:** wronggmail / anypass

**Steps:**
1. Enter invalid email
2. Click Login

**Expected Result:**
Email validation message

**Actual Result:**
No validation

**Status:** Fail
**Priority:** High

---

### ❌ TC04: Login with empty fields

**Steps:**
1. Click login without entering data

**Expected Result:**
Required field message

**Actual Result:**
No message

**Status:** Fail
**Priority:** High

---

### ❌ TC05: Login with only email

**Steps:**
1. Enter email only
2. Click Login

**Expected Result:**
Password required

**Actual Result:**
No message

**Status:** Fail
**Priority:** Medium

---

### ❌ TC06: Login with only password

**Steps:**
1. Enter password only
2. Click Login

**Expected Result:**
Email required

**Actual Result:**
No message

**Status:** Fail
**Priority:** Medium

---

### ❌ TC07: Login with very long password

**Steps:**
1. Enter 50+ character password
2. Click Login

**Expected Result:**
System should restrict

**Actual Result:**
Accepted

**Status:** Fail
**Priority:** Low

---

### ❌ TC08: Login with special characters

**Steps:**
1. Enter special characters
2. Click Login

**Expected Result:**
Proper validation

**Actual Result:**
No validation

**Status:** Fail
**Priority:** Medium

---

### ✅ TC09: Forgot Password link

**Steps:**
1. Click "Forgot Password"

**Expected Result:**
Navigate to reset page

**Actual Result:**
Navigated

**Status:** Pass
**Priority:** Low

---

### ✅ TC10: Create Account link

**Steps:**
1. Click "Create Account"

**Expected Result:**
Navigate to signup page

**Actual Result:**
Navigated

**Status:** Pass
**Priority:** Low