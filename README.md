# Jumia Checkout & Payment System Testing
## Capstone Project Summary Report

This repository details the final manual test execution results for Jumia's core e-commerce transaction funnel. Testing focused on evaluating critical user journeys across four primary modules: Cart Management, Checkout Flow, Payment Gateway, and System Resilience.

A total of 15 test cases were executed. The system achieved a 100% pass rate with 0 failed tests and 0 open bugs, demonstrating high stability and readiness for deployment under the verified scopes.

### 📊 Test Metrics Dashboard

| Metric | Value |
| :--- | :--- |
| **Total Test Cases Executed** | 15 |
| **Total Passed** | 15 |
| **Total Failed** | 0 |
| **Pass Rate** | 100.00% |
| **Open Bugs** | 0 |

### ⚙️ Module Performance Breakdown
* **Cart Management (4/4 Passed):** Successfully verified core cart operations including adding items, removing items, dynamically updating quantities to maximum stock levels, and blocking manual empty-cart checkout navigation.
* **Checkout Flow (3/3 Passed):** Validated data entry handling for happy-path deliveries, mandatory field inline error validation, and proper application of valid promo codes.
* **Payment Gateway (5/5 Passed):** Confirmed seamless transaction processing across multiple methods (Credit Card, Pay on Delivery). Processed negative-testing scenarios, including transaction declines due to insufficient funds and expired card validation blockages.
* **System Resilience (3/3 Passed):** Verified that the system gracefully handles unexpected interruptions, including session timeouts, page refreshes during live payment processing, and sudden network disconnections mid-checkout without duplicating orders or crashing.

### 🛠 Core QA Competencies Demonstrated
* Functional Testing & Boundary Value Analysis (BVA)
* Negative Testing & Error Handling Verification
* System Edge-Case & E-commerce Funnel Resilience Evaluation
* Professional Test Documentation & Execution Metrics Reporting

