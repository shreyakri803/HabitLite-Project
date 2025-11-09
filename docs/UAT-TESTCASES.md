# UAT Test Cases – HabitLite  
Version: 1.0  
Owner: Shreya  
Date: 09/11/2025

## 1. Purpose
This UAT (User Acceptance Testing) pack ensures that the HabitLite MVP behaves as expected and meets defined acceptance criteria before release.

---

## 2. Test Summary
UAT validates core functions:
- Habit creation  
- Habit editing  
- Habit deletion  
- Daily tracking  
- LocalStorage persistence  
- Weekly summary calculations  
- CSV export  

---

## 3. Test Cases

### ✅ TC01 – Add a New Habit
**Precondition:** App is loaded  
**Steps:**  
1. Click “Add Habit”  
2. Enter habit name  
3. Save  
**Expected Result:** Habit appears in the list  
**Status:** Pass / Fail  

---

### ✅ TC02 – Edit Habit
**Steps:**  
1. Select habit  
2. Click “Edit”  
3. Change name  
4. Save  
**Expected Result:** Habit name updated in UI  
**Status:** Pass / Fail  

---

### ✅ TC03 – Delete Habit
**Steps:**  
1. Select habit  
2. Click “Delete”  
**Expected Result:** Habit removed after confirmation  
**Status:** Pass / Fail  

---

### ✅ TC04 – Mark Habit Complete (Daily Toggle)
**Steps:**  
1. Tap checkbox for today  
**Expected Result:** Checkbox shows completed state  
**Status:** Pass / Fail  

---

### ✅ TC05 – LocalStorage Data Persistence
**Steps:**  
1. Mark a habit  
2. Refresh browser  
**Expected Result:** Habit remains marked after refresh  
**Status:** Pass / Fail  

---

### ✅ TC06 – Weekly Summary View
**Steps:**  
1. Complete habits over multiple days  
2. Open "Weekly Summary"  
**Expected Result:** Weekly counts and streak match actual data  
**Status:** Pass / Fail  

---

### ✅ TC07 – CSV Export
**Steps:**  
1. Click CSV export button  
**Expected Result:** CSV file downloads with accurate history  
**Status:** Pass / Fail  

---

### ✅ TC08 – Mobile Responsiveness
**Steps:**  
1. Open app in mobile view  
**Expected Result:** Buttons, text, and layout remain clean & usable  
**Status:** Pass / Fail  

---

## 4. UAT Sign-Off
UAT Completed By: Shreya 
Date: 09/11/2025
Approval: ✅ Approved

