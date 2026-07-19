# 🍔 Flame & Crust Web Application - QA Documentation

Welcome to the official QA Testing and Defect Documentation repository for the **Flame & Crust Web Application**. This repository contains the complete end-to-end software quality assurance deliverables executed during the July 2026 testing cycle.

---

## 📁 Repository Structure & Contents

All project deliverables have been organized systematically into the following main categories:

### 1. 📊 QA Deliverables (`/tasks`)
This folder contains the core testing artifacts and compliance documents:
*   **`Task_01_Functional_Test_Cases.xlsx`** – The master test suite containing 13 comprehensive functional test scenarios (covering authentication, cart operations, and checkout logic).
*   **`Task_02_API_Technical_Test_Notes.xlsx`** – Technical test cases and structural boundary analysis for integration endpoints.
*   **`Task_03_04_Bug_Report.xlsx`** – The complete Defect Log capturing all 9 unique bugs found during functional and cross-browser execution.
*   **`Task_05_Risk_Matrix.xlsx`** – Defect priority assessment mapping impact vs. urgency.
*   **`Task_06_Test_Summary_Report.pdf`** – The final execution summary sign-off, risk evaluation, and recommendations.

### 📸 2. Test Evidence (`/evidence`)
Contains full media proof (Screenshots and Screen Recordings) validating the 9 logged defects from **BUG-001** to **BUG-009**. Each file is explicitly named after its respective Defect ID for trace-ability.

---

## 📈 Test Cycle Summary

*   **Total Master Test Cases:** 13
*   **Total Passed Cases:** 12 
*   **Total Failed Cases:** 1 
*   **Total Logged Defects:** 9 Unique Bugs (1 Critical, 4 High, 4 Medium)
*   **Final Release Status:** 🔴 **NOT READY TO SHIP** (Retested pending critical third-party Uber API and reservation logic hot-fixes).

---

## 💻 Tech Stack & Environments Tested
*   **Desktop Viewports:** Google Chrome, Microsoft Edge 
*   **Mobile Viewports:** Responsive Emulation (iPhone 12 layout matrices via Chrome DevTools)
*   **Execution Tools:** Manual UI/UX Validation, Postman API Contract Verification
