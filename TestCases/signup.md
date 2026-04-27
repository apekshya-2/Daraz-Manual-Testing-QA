# Daraz Signup Test Cases

## TS02: Signup Validation

---

### ✅ TC01: Signup with valid data
**Steps:**
1. Enter valid name, email, password, confirm password  
2. Click Signup  

**Expected:** Account should be created  
**Actual:** Account created  
**Status:** Pass  
**Priority:** High  

---

### ❌ TC02: Signup with empty fields
**Steps:**
1. Click signup without entering data  

**Expected:** Required field messages  
**Actual:** No validation shown  
**Status:** Fail  
**Priority:** High  

---

### ❌ TC03: Invalid email format
**Steps:**
1. Enter invalid email  
2. Click Signup  

**Expected:** Email validation message  
**Actual:** No validation shown  
**Status:** Fail  
**Priority:** High  

---

### ❌ TC04: Weak password
**Steps:**
1. Enter weak password  
2. Click Signup  

**Expected:** Password strength message  
**Actual:** Accepted weak password  
**Status:** Fail  
**Priority:** Medium  

---

### ❌ TC05: Password mismatch
**Steps:**
1. Enter different password & confirm  
2. Click Signup  

**Expected:** Mismatch message  
**Actual:** No message  
**Status:** Fail  
**Priority:** High  

---

### ❌ TC06: Name with numbers
**Expected:** Name validation  
**Actual:** Accepted numbers  
**Status:** Fail  

---

### ❌ TC07: Special characters in name
**Expected:** Validation message  
**Actual:** No validation  

---

### ❌ TC08: Very long name
**Expected:** System should restrict  
**Actual:** Accepted input  

---

### ❌ TC09: Already registered email
**Expected:** "Email already exists"  
**Actual:** No message  

---

### ❌ TC10: Partial data
**Expected:** Required message  
**Actual:** No validation  