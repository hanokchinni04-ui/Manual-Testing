# 🛒 Automation Exercise – Manual QA Testing Project

Manual functional testing project for the e-commerce demo site **[Automation Exercise](https://www.automationexercise.com)**, built to demonstrate an end-to-end manual QA workflow — from requirement analysis through test design, execution, and defect reporting.

## 📌 About This Project

This project simulates a real-world manual testing engagement. Rather than just following the site's own published test case list, it independently analyzes the application's core flows and builds out full QA documentation — the same artifacts a QA engineer would produce and hand off to a team in a live project.

**Application Under Test:** [automationexercise.com](https://www.automationexercise.com)
**Testing Type:** Manual, Black-Box
**Status:** Completed

## 🎯 Objectives

- Validate that core e-commerce flows work as expected: registration, login, search, cart, checkout, and payment
- Identify and document real defects with clear reproduction steps
- Produce professional QA deliverables suitable for team handoff and stakeholder review
- Practice structured test design: scenario mapping, requirement traceability, and defect triage

## 🧩 Scope

**In Scope**
- User Registration & Login
- Home Page & Navigation
- Product Search, Filters & Product Details
- Shopping Cart
- Checkout & Payment
- Account Management
- Newsletter & Contact Us
- Cross-browser sanity checks (Chrome, Firefox)

**Out of Scope**
- REST API testing
- Performance / load testing
- Security penetration testing
- Backend / admin functionality

## 📂 Repository Contents

| File | Description |
|---|---|
| `Test_Plan_AutomationExercise.docx` | Test strategy, scope, approach, environment, roles, entry/exit criteria, risks, and schedule |
| `Test_Scenarios_AutomationExercise.docx` | 29 high-level test scenarios across 7 functional modules |
| `Test_Cases_AutomationExercise.xlsx` | 38 detailed test cases with steps, expected results, and execution status (README + status legend + one sheet per module) |
| `Bug_Report_AutomationExercise.xlsx` | Defect log with severity/priority/status, plus a summary dashboard |

## 🗂️ Modules Covered

1. User Registration & Login
2. Home Page & Navigation
3. Product Search & Browsing
4. Shopping Cart
5. Checkout & Payment
6. Account Management
7. Support Features & Cross-Browser Compatibility

## 📊 Results Summary

| Metric | Value |
|---|---|
| Test Scenarios | 29 |
| Test Cases Executed | 38 |
| Pass Rate | ~97% |
| Defects Logged | 3 (0 Critical, 1 High-priority, 2 Low) |

## 🐞 Sample Defect

> **BUG-001** — Contact Us form submits successfully even when the Email field is left empty. Expected: form should block submission with a validation message. Severity: Medium | Priority: High | Status: Open

## 🛠️ Approach

Testing was performed manually using black-box techniques — equivalence partitioning, boundary value analysis, and exploratory testing — covering both positive (expected use) and negative (invalid input / error handling) paths for every in-scope module.



