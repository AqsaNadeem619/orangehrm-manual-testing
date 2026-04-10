# Test Plan — OrangeHRM Manual Testing
**Version:** 1.0  
**Date:** [Your date]  
**Prepared by:** Aqsa Nadeem  

---

## 1. Objective
To manually test the core modules of OrangeHRM (open-source HR software) and verify that features work as expected, edge cases are handled, and defects are properly documented.

---

## 2. Scope

### In Scope (what we ARE testing)
- Login / Logout
- Employee Management (Add, Edit, Search, Delete employee)
- Leave Management (Apply leave, approve leave, leave balance)
- Recruitment (Add job vacancy, view applicants)

### Out of Scope (what we are NOT testing)
- Performance / load testing
- Mobile responsiveness
- Third-party integrations

---

## 3. Test Approach
- **Type:** Manual Black Box Testing
- **Technique:** Equivalence Partitioning, Boundary Value Analysis, Exploratory Testing
- **Environment:** Chrome browser, Windows 10, OrangeHRM demo site

---

## 4. Entry Criteria (when do we START testing?)
- Application is accessible at the demo URL
- Login credentials are working
- Test cases are written and reviewed

## 5. Exit Criteria (when do we STOP testing?)
- All planned test cases have been executed
- All critical and high severity bugs are reported
- Test summary report is completed

---

## 6. Test Deliverables
- This test plan
- Test cases (Google Sheet / Excel)
- Bug reports (JIRA)
- Test summary report

---

## 7. Schedule
| Activity | Duration |
|---|---|
| Exploratory testing (understand app) | Day 1 |
| Write test cases | Day 2 |
| Execute test cases | Day 3–4 |
| Log bugs in JIRA | Day 3–4 |
| Write test summary | Day 5 |

---

## 8. Risks
| Risk | Mitigation |
|---|---|
| Demo site may be down | Test during off-peak hours, note downtime |
| Demo data may reset | Re-create test data before each session |

---

## 9. Tools
- Browser: Google Chrome
- Bug Tracking: JIRA
- Documentation: Google Docs / GitHub
- Screenshots: Snipping Tool / Lightshot
