# OrangeHRM — Manual Testing Project

**Type:** Manual Black Box Testing  
**Tester:** Aqsa Nadeem  
**Tools:** JIRA · Google Sheets · Chrome DevTools · Lightshot  
**Status:** Completed  

---

## What is this project?

This is a manual QA project where I tested the core modules of **OrangeHRM** — an open-source HR management system. The goal was to simulate a real-world testing cycle from scratch: writing a test plan, designing test cases, executing them, logging bugs, and producing a final summary report.

OrangeHRM was chosen because it is a feature-rich, real-world application with multiple modules, user roles, and workflows — making it ideal for building and demonstrating manual testing skills.

**Live demo site used:** https://opensource-demo.orangehrmlive.com  
**Login:** Admin / admin123

---

## Modules Tested

| Module | Test Cases Written | Bugs Found |
|---|---|---|
| Login / Logout | 20 | 2 |
| Employee Management | 15 | 1 |
| Leave Management | 12 | 2 |
| Recruitment | 8 | 1 |
| **Total** | **55** | **6** |

---

## What I Tested (Test Coverage)

- **Positive scenarios** — valid inputs, expected user flows
- **Negative scenarios** — invalid inputs, wrong credentials, missing fields
- **Edge cases** — very long inputs, special characters, SQL injection attempts
- **UI/UX** — error message clarity, field validation, keyboard navigation
- **Security basics** — session handling, access control, input sanitization

---

## Bugs Found (Summary)

| Bug ID | Module | Title | Severity | Priority | Status |
|---|---|---|---|---|---|
| BUG-001 | Login | Error message exposes system info on SQL injection input | High | High | Open |
| BUG-002 | Login | No account lockout after 5 failed login attempts | Medium | High | Open |
| BUG-003 | Employee | Search returns results for deleted employees | Medium | Medium | Open |
| BUG-004 | Leave | Leave balance does not update immediately after approval | High | High | Open |
| BUG-005 | Leave | Applying leave with past date shows no validation error | Low | Medium | Open |
| BUG-006 | Recruitment | Job vacancy form submits with empty required fields | High | High | Open |

> Full bug reports with steps to reproduce, screenshots, and severity justification are in the `/Bug-Reports` folder.

---

## Project Structure

```
orangehrm-manual-testing/
│
├── README.md                          ← you are here
├── Test-Plan.md                       ← scope, approach, entry/exit criteria
│
├── Test-Cases/
│   ├── Login-TestCases.csv            ← 20 test cases
│   ├── Employee-TestCases.csv         ← 15 test cases
│   ├── Leave-TestCases.csv            ← 12 test cases
│   └── Recruitment-TestCases.csv      ← 8 test cases
│
├── Bug-Reports/
│   ├── BUG-001-SQL-Injection.md
│   ├── BUG-002-Account-Lockout.md
│   ├── BUG-003-Deleted-Employee-Search.md
│   ├── BUG-004-Leave-Balance.md
│   ├── BUG-005-Past-Date-Leave.md
│   ├── BUG-006-Empty-Form-Submit.md
│   └── screenshots/
│
└── Test-Summary.md                    ← final report with metrics
```

---

## Test Execution Results

| Result | Count |
|---|---|
| Pass | 47 |
| Fail | 6 |
| Blocked | 2 |
| **Total Executed** | **55** |

**Pass rate:** 85%

---

## Key Learnings

- Practiced end-to-end test cycle: plan → design → execute → report
- Learned to distinguish severity vs priority in real scenarios
- Identified security-related edge cases (SQL injection, session handling)
- Used JIRA to manage full defect lifecycle from New to Closed
- Built habit of validating actual result against expected result for every test case

---

## Tools Used

| Tool | Purpose |
|---|---|
| JIRA | Bug tracking and defect lifecycle management |
| Google Sheets | Test case documentation and execution tracking |
| Chrome DevTools | Inspecting network requests and console errors |
| Lightshot | Screenshots for bug evidence |
| GitHub | Version control and portfolio hosting |

---

## About the Tester

I am a Technical Writer transitioning into QA, with 3+ years of experience documenting SaaS and AI platforms. This project is part of my structured 90-day QA transition plan.

📧 aqsanadeem619@gmail.com  
🔗 [LinkedIn](#)  
🔗 [Upwork Profile](#)
