# Daraz Search Bar Test Cases

## TS03: Search Functionality

---

### ✅ TC01: Valid keyword search
**Expected:** Relevant products  
**Actual:** Products displayed  
**Status:** Pass  

---

### ❌ TC02: Empty search
**Expected:** Validation / no action  
**Actual:** Search runs  
**Status:** Fail  

---

### ❌ TC03: Special characters
**Expected:** No results / validation  
**Actual:** Irrelevant results  
**Status:** Fail  

---

### ❌ TC04: Very long text
**Expected:** Restriction  
**Actual:** Search executed  
**Status:** Fail  

---

### ❌ TC05: Only spaces
**Expected:** Validation  
**Actual:** Search executed  
**Status:** Fail  

---

### ✅ TC06: Uppercase search
**Expected:** Case insensitive  
**Actual:** Works  
**Status:** Pass  

---

### ✅ TC07: Partial keyword
**Expected:** Suggestions  
**Actual:** Works  
**Status:** Pass  

---

### ✅ TC08: Enter key search
**Expected:** Results display  
**Actual:** Works  
**Status:** Pass  

---

### ❌ TC09: Non-existing product
**Expected:** "No results found"  
**Actual:** No message  
**Status:** Fail  

---

### ✅ TC10: Clear search
**Expected:** Clears  
**Actual:** Cleared  
**Status:** Pass  