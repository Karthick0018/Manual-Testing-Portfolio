# Test Plan - US Healthcare RCM - Payment Posting, Denials and AR

## 1. Objective
Revenue Cycle Management application: ERA/EOB payment posting, denial management and accounts receivable follow-up.

## 2. Scope
In scope:
- Payment Posting
- Denial Management
- AR Follow-up
- Reports & Audit

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
- RCM_Test_Cases.xlsx (test cases, traceability matrix, execution summary)
- RCM_Bug_Report.xlsx
- This test plan
