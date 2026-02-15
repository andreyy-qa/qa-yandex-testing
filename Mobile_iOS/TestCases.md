# Test Cases – Yandex Mobile (iOS)

---

## TC-01 – Open Tab Manager

**Precondition:**  
Application is launched.

**Steps:**  
1. Tap Tab Manager icon.

**Expected Result:**  
All opened tabs are displayed correctly.

---

## TC-02 – Create New Tab

**Precondition:**  
Application is launched.

**Steps:**  
1. Open Tab Manager.
2. Tap "New Tab".

**Expected Result:**  
New tab is created and becomes active.

---

## TC-03 – Incognito Mode Session Isolation

**Precondition:**  
Application is launched.

**Steps:**  
1. Open Incognito mode.
2. Open several pages.
3. Close application.
4. Re-open Incognito mode.

**Expected Result:**  
Previous Incognito session is not restored.

---

## TC-04 – Auto-Translation Activation

**Precondition:**  
Open webpage in foreign language.

**Steps:**  
1. Trigger auto-translation.
2. Wait for translation to complete.

**Expected Result:**  
Page content is translated correctly without layout breaking.

---

## TC-05 – Smart Camera Recognition

**Precondition:**  
Camera permission granted.

**Steps:**  
1. Open Smart Camera.
2. Scan QR code.

**Expected Result:**  
QR code is recognized and correct action is triggered.
