# 🐞 Daraz Login Page - Bug Reports

---

## BUG-01: No error message for invalid password

**Test Case ID:** TC02
**Severity:** High
**Priority:** High
**Screenshot:** /Screenshots/bug01.png

**Steps to Reproduce:**
1. Enter valid email
2. Enter wrong password
3. Click Login

**Expected Result:**
Error message should display

**Actual Result:**
No message shown

**Status:** Open

---

## BUG-02: No validation for invalid email

**Test Case ID:** TC03
**Severity:** Medium
**Priority:** High
**Screenshot:** /Screenshots/bug02.png

**Steps to Reproduce:**
1. Enter invalid email
2. Click Login

**Expected Result:**
Email validation message

**Actual Result:**
No validation

**Status:** Open

---

## BUG-03: Login with empty fields

**Test Case ID:** TC04
**Severity:** High
**Priority:** High
**Screenshot:** /Screenshots/bug03.png

**Steps to Reproduce:**
1. Click login without entering any data

**Expected Result:**
Required field message

**Actual Result:**
No message

**Status:** Open

---

## BUG-04: Login with only email

**Test Case ID:** TC05
**Severity:** High
**Priority:** High
**Screenshot:** /Screenshots/bug04.png

**Steps to Reproduce:**
1. Enter email only
2. Click Login

**Expected Result:**
Password required message

**Actual Result:**
No message

**Status:** Open

---

## BUG-05: Login with only password

**Test Case ID:** TC06
**Severity:** High
**Priority:** High
**Screenshot:** /Screenshots/bug05.png

**Steps to Reproduce:**
1. Enter password only
2. Click Login

**Expected Result:**
Email required message

**Actual Result:**
No message

**Status:** Open

---

## BUG-06: System accepts very long password

**Test Case ID:** TC07
**Severity:** Low
**Priority:** Medium
**Screenshot:** /Screenshots/bug06.png

**Steps to Reproduce:**
1. Enter password with 50+ characters
2. Click Login

**Expected Result:**
System should restrict long password

**Actual Result:**
Accepted

**Status:** Open

---

## BUG-07: No validation for special characters

**Test Case ID:** TC08
**Severity:** Low
**Priority:** Medium
**Screenshot:** /Screenshots/bug07.png

**Steps to Reproduce:**
1. Enter special characters
2. Click Login

**Expected Result:**
Proper validation

**Actual Result:**
No validation

**Status:** Open