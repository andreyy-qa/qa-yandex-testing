# Bug Reports – ya.ru (Desktop)

---

## BUG-01 – Technical Page Displayed for Whitespace Query

**Environment:**  
Desktop browser (Chrome)

**Precondition:**  
Main page is opened.

**Steps to Reproduce:**
1. Enter only whitespace in search field.
2. Press Enter.

**Expected Result:**  
Search request should not execute. User should see validation message or no action.

**Actual Result:**  
User is redirected to internal technical page.

**Severity:** Medium  
**Priority:** High

---

## BUG-02 – Search Executed with Empty Query After Multiple Spaces

**Environment:**  
Desktop browser (Chrome)

**Precondition:**  
Main page is opened.

**Steps to Reproduce:**
1. Enter multiple spaces.
2. Delete part of spaces.
3. Press Enter.

**Expected Result:**  
System should validate input and prevent empty search execution.

**Actual Result:**  
Search request is executed despite invalid input.

**Severity:** Medium  
**Priority:** Medium

---

## BUG-03 – Infinite Feed Performance Degradation During Long Scroll

**Environment:**  
Desktop browser (Chrome)

**Precondition:**  
Main page is opened.

**Steps to Reproduce:**
1. Scroll continuously for several minutes.
2. Monitor page behavior.

**Expected Result:**  
Feed should load smoothly without UI lag.

**Actual Result:**  
Page responsiveness decreases and scrolling becomes unstable.

**Severity:** Low  
**Priority:** Low
