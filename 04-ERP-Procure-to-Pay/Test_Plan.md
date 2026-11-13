# Test Plan - ERP - Procure to Pay (P2P)

## 1. Objective
ERP procurement cycle: purchase requisition, purchase order, goods receipt and vendor invoice with three-way match.

## 2. Scope
In scope:
- Purchase Requisition
- Purchase Order
- Goods Receipt
- Invoice & Payment

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
- P2P_Test_Cases.xlsx (test cases, traceability matrix, execution summary)
- P2P_Bug_Report.xlsx
- This test plan
