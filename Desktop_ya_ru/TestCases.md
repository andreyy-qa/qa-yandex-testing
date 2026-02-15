# Test Cases – ya.ru (Desktop)

---

## TC-01 – Search Using Enter Key

**Precondition:**  
Main page is opened.

**Steps:**  
1. Enter valid search query.  
2. Press Enter.

**Expected Result:**  
User is redirected to search results page.

---

## TC-02 – Search Using Search Button

**Precondition:**  
Main page is opened.

**Steps:**  
1. Enter valid search query.  
2. Click search button.

**Expected Result:**  
User is redirected to search results page.

---

## TC-03 – Search with Whitespace Only

**Precondition:**  
Main page is opened.

**Steps:**  
1. Enter only spaces in search field.  
2. Press Enter.

**Expected Result:**  
Search should not execute. Validation message should appear or request should be ignored.

---

## TC-04 – Suggestion Selection

**Precondition:**  
Main page is opened.

**Steps:**  
1. Start typing query.  
2. Select suggestion from autocomplete list.

**Expected Result:**  
Selected suggestion is inserted and search results page is opened.

---

## TC-05 – Infinite Feed Stability

**Precondition:**  
Main page is opened.

**Steps:**  
1. Scroll down continuously for several minutes.

**Expected Result:**  
Content loads dynamically without UI freezing or layout breaking.
