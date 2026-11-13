# Test Plan - Loan Management System

## 1. Objective
Loan lifecycle: application, eligibility, EMI calculation, approval workflow and repayment.

## 2. Scope
In scope:
- Loan Application
- Eligibility & EMI
- Approval Workflow
- Repayment

Out of scope: performance, load and automation testing.

## 3. Test Approach
- Test levels: functional, regression, smoke and sanity
- Techniques: boundary value analysis, equivalence partitioning, negative testing, error guessing
- Test design: requirement-based test cases with traceability matrix
- Defect tracking: JIRA (sample report in Excel)
- Test management: QTest (sample cases in Excel)

## 4. Entry Criteria
- Requirements reviewed and signed off
- Build deployed and smoke test passed
- Test data available

## 5. Exit Criteria
- All high-priority test cases executed
- No open Critical or High defects
- Test summary report shared

## 6. Defect Severity
| Severity | Meaning |
|---|---|
| Critical | Blocks core flow, data loss or security risk |
| High | Major function wrong, no workaround |
| Medium | Function wrong, workaround available |
| Low | Cosmetic or minor |

## 7. Deliverables
- LMS_Test_Cases.xlsx (test cases, traceability matrix, execution summary)
- LMS_Bug_Report.xlsx
- This test plan
