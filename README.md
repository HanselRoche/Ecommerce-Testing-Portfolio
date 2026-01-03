# 🛒 E-Commerce Testing Portfolio
**Author:** Hansel Roche  
**System Tested:** [Swag Labs (SauceDemo)](https://www.saucedemo.com/)

## 📄 Overview
This repository contains a manual testing portfolio demonstrating **Functional**, **UI**, and **Security** testing on an e-commerce platform. It includes a full test suite, executed test cases, and documented defect reports with evidence.

## 📂 Key Artifacts

### 1. 📊 Master Test Suite
**[View Full Test Suite (Excel)](./Hansel_Roche_Test_Suite.xlsx)**
* **Total Test Cases:** 25
* **Modules Covered:** Login, Inventory, Cart, Checkout, Payments, Navigation.
* **Status:** 21 PASS / 4 FAIL

---

### 2. 🐞 Defect Reports & Evidence
The following critical bugs were identified, documented, and reported. Click the **Folder** links to view the detailed **Defect Report** and **Screenshots** for each bug.

| Bug ID | Severity | Module | Summary of Defect | Evidence Folder |
| :--- | :--- | :--- | :--- | :--- |
| **BUG_001** | Medium | Checkout | **Input Validation:** Zip Code field accepts invalid special characters (e.g., "!!!!"). | [📂 Open TC_002](./TC_002) |
| **BUG_002** | Low | UI | **Visual Bug:** 'Problem_User' sees incorrect 'Dog' placeholder images for all products. | [📂 Open TC_012](./TC_012) |
| **BUG_003** | Medium | State Logic | **UX/State:** 'Reset App State' clears cart data but fails to reset UI button states. | [📂 Open TC_018](./TC_018) |
| **BUG_004** | Medium | Business Logic | **Validation:** System allows checkout process to initiate with an empty cart. | [📂 Open TC_020](./TC_020) |

---

### 3. 🛠️ Tools & Environment
* **Test Management:** Excel (Test Case Design & Execution Log)
* **Browser:** Brave Browser (Version 1.61)
* **Debugging:** Chrome/Brave Developer Tools (Console Logs & Element Inspection)
* **Bug Tracking:** GitHub (Repository as Portfolio)

---
