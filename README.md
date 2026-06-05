<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=gradient&customColorList=6,11,20,24,30&text=CRM%20Product%20Testing&fontSize=42&fontAlignY=38&desc=QA%20Portfolio%20Project%20%7C%20Manual%20Testing%20%7C%20Frontend%20Validation&descAlignY=60&animation=fadeIn" alt="CRM Product Testing Banner" />

<br />

![QA Testing](https://img.shields.io/badge/QA-Product%20Testing-FF6B6B?style=for-the-badge)
![CRM](https://img.shields.io/badge/CRM-Business%20Workflows-4D96FF?style=for-the-badge)
![Manual Testing](https://img.shields.io/badge/Manual%20Testing-Test%20Cases-6BCB77?style=for-the-badge)
![UI Testing](https://img.shields.io/badge/UI%2FUX-Frontend%20Testing-F7B801?style=for-the-badge)
![Regression](https://img.shields.io/badge/Regression-Quality%20Checks-9B5DE5?style=for-the-badge)

### A vibrant QA documentation project for testing CRM workflows, frontend usability, business logic, and product stability.

</div>

---

## 🌟 Project Snapshot

This repository showcases a structured **CRM Product Testing** project designed to validate customer relationship management workflows from both **business** and **end-user** perspectives.

The project focuses on testing important CRM modules such as **Login, Leads, Contacts, Accounts, Opportunities, Tasks, Reports, Dashboards, Notifications, and Role-Based Access Control**.

> [!NOTE]
> This README is designed for a GitHub portfolio/profile presentation and can be used to demonstrate QA testing knowledge, CRM domain understanding, documentation skills, and frontend product validation experience.

---

## 🎯 Project Goals

| Goal | Description |
|---|---|
| ✅ Validate CRM workflows | Ensure core CRM features work correctly across sales, support, marketing, and admin flows. |
| 🎨 Improve frontend experience | Check UI consistency, responsiveness, forms, messages, buttons, navigation, and usability. |
| 🐞 Identify defects | Report functional, validation, UI, usability, security, and data-related issues clearly. |
| 🔐 Verify permissions | Confirm users only access features allowed by their role. |
| 📊 Check business accuracy | Validate dashboards, reports, sales pipeline updates, and customer data mapping. |
| 🚀 Support release quality | Help improve product stability before production release. |

---

## 🧩 Modules Covered

<div align="center">

| 🔐 Login | 👤 Leads | 📇 Contacts | 🏢 Accounts |
|---|---|---|---|
| Authentication | Lead Creation | Contact Updates | Account Linking |
| Error Handling | Lead Assignment | Search & Filter | Related Contacts |

| 💼 Opportunities | 📝 Tasks | 📊 Reports | ⚙️ Admin |
|---|---|---|---|
| Sales Pipeline | Follow-ups | Dashboards | User Roles |
| Stage Updates | Reminders | Exports | Permissions |

</div>

---

## 🎨 Frontend UI Testing Focus

| Area | What Was Tested |
|---|---|
| **Layout & Alignment** | Page structure, spacing, alignment, visual hierarchy, and component placement. |
| **Forms & Inputs** | Mandatory fields, field validation, placeholders, dropdowns, checkboxes, and error messages. |
| **Buttons & Actions** | Button visibility, hover behavior, click actions, disabled states, and confirmation prompts. |
| **Navigation Flow** | Sidebar menus, breadcrumbs, page routing, back navigation, and module switching. |
| **Responsiveness** | CRM usability on desktop, laptop, tablet, and mobile screens. |
| **User Feedback** | Toast messages, success alerts, validation warnings, loaders, and empty states. |
| **Visual Consistency** | Font usage, color consistency, icon alignment, table design, modal design, and spacing. |

---

## 🧪 Testing Types Performed

```mermaid
mindmap
  root((CRM Testing))
    Functional Testing
      Login
      Leads
      Contacts
      Opportunities
      Reports
    UI and Usability Testing
      Layout
      Forms
      Navigation
      Responsiveness
    Regression Testing
      Retesting Fixed Bugs
      Build Verification
      Impact Analysis
    Security Testing
      Role Access
      Unauthorized Pages
      Session Timeout
    Data Validation
      Mandatory Fields
      Duplicate Records
      Import Export
```

---

## 🔄 QA Workflow

```mermaid
flowchart LR
    A[Requirement Review] --> B[Test Scenario Design]
    B --> C[Test Case Creation]
    C --> D[Test Execution]
    D --> E[Bug Reporting]
    E --> F[Retesting]
    F --> G[Regression Testing]
    G --> H[Test Closure Report]
```

---

## 📌 Test Scenarios

| Module | Scenario | Expected Result |
|---|---|---|
| Login | User logs in with valid credentials | User should be redirected to the CRM dashboard. |
| Login | User enters invalid credentials | A clear error message should be displayed. |
| Leads | User creates a new lead with valid data | Lead should be saved successfully. |
| Leads | User converts a lead into an opportunity | Opportunity should be created with correct lead details. |
| Contacts | User updates contact information | Updated details should be saved and displayed. |
| Accounts | User links contacts to an account | Contacts should appear under the selected account. |
| Opportunities | User changes the sales stage | Pipeline stage should update correctly. |
| Tasks | User creates a follow-up task | Task should be visible in the activity list. |
| Reports | User generates a sales report | Report should display accurate CRM data. |
| Permissions | Restricted user accesses admin settings | Access should be denied. |

---

## 🧾 Sample Test Case Format

| Test Case ID | Module | Test Scenario | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC_CRM_001 | Login | Verify login with valid credentials | Enter valid email and password, then click Login | Valid user credentials | User should log in successfully | As expected | Pass |
| TC_CRM_002 | Leads | Verify lead creation | Open Leads, click Add Lead, enter required details, then save | Lead name, email, phone | New lead should be created | As expected | Pass |
| TC_CRM_003 | Contacts | Verify mandatory field validation | Open Add Contact and submit without required fields | Blank required fields | Validation message should appear | As expected | Pass |
| TC_CRM_004 | Opportunities | Verify stage update | Open Opportunity, change stage, then save | Opportunity record | Stage should update correctly | As expected | Pass |

---

## 🐞 Bug Report Template

```text
Bug ID: BUG_CRM_001
Title: Lead conversion fails when the email field is empty
Module: Leads
Severity: High
Priority: High
Environment: QA
Build Version: v1.0.0

Steps to Reproduce:
1. Log in to the CRM application.
2. Open the Leads module.
3. Create a lead without an email address.
4. Try to convert the lead into an opportunity.

Expected Result:
The system should either allow conversion with available details or show a clear validation message.

Actual Result:
The page freezes and the opportunity is not created.

Status: Open
Assigned To: Development Team
```

---

## 🛠️ Tools & Technologies

<div align="center">

| Category | Tools |
|---|---|
| Test Case Management | Excel, Google Sheets, TestRail, Zephyr |
| Bug Tracking | Jira, Bugzilla, Trello, GitHub Issues |
| API Testing | Postman |
| Database Validation | SQL |
| Browser Testing | Chrome, Firefox, Edge, Safari |
| Automation Exposure | Selenium, Cypress, Playwright |
| Documentation | Markdown, GitHub README, Test Reports |

</div>

---

## 🌐 Test Environment

| Component | Details |
|---|---|
| Application Type | CRM Web Application |
| Environment | QA / Staging |
| Browsers | Chrome, Firefox, Edge |
| Devices | Desktop, Laptop, Mobile, Tablet |
| Operating Systems | Windows, macOS, Android, iOS |
| Network | Stable internet connection |

---

## 📊 Test Execution Dashboard

| Metric | Count | Status |
|---|---:|---|
| Total Test Cases | 0 | 📝 To be updated |
| Passed | 0 | ✅ To be updated |
| Failed | 0 | ❌ To be updated |
| Blocked | 0 | ⛔ To be updated |
| Defects Reported | 0 | 🐞 To be updated |
| Defects Closed | 0 | 🎯 To be updated |

> Update these numbers after every testing cycle.

---

## 🚨 Risk Areas

| Risk | Impact |
|---|---|
| Incorrect customer data mapping | Wrong business decisions and poor user trust. |
| Duplicate leads or contacts | Confusing sales records and reporting errors. |
| Permission leakage | Unauthorized users may access sensitive data. |
| Broken sales pipeline updates | Sales progress may be tracked incorrectly. |
| Inaccurate dashboard data | Reports may mislead stakeholders. |
| Missed reminders or notifications | Follow-ups may be delayed or lost. |
| Failed integrations | Email, calendar, or third-party workflows may break. |

---

## 📦 Deliverables

- Test Plan
- Test Scenarios
- Test Cases
- Bug Reports
- Regression Test Suite
- Test Execution Summary
- Test Closure Report
- Defect Evidence Screenshots

---

## 🗂️ Repository Structure

```text
CRM-Product-Testing/
├── README.md
├── Test-Plan/
│   └── CRM_Test_Plan.md
├── Test-Cases/
│   └── CRM_Test_Cases.xlsx
├── Bug-Reports/
│   └── CRM_Bug_Report_Template.md
├── Test-Scenarios/
│   └── CRM_Test_Scenarios.md
├── Reports/
│   └── Test_Execution_Summary.md
└── Screenshots/
    └── defect-evidence/
```

---

## 💡 Skills Demonstrated

<div align="center">

![Manual Testing](https://img.shields.io/badge/Manual%20Testing-Experienced-FF6B6B?style=flat-square)
![Functional Testing](https://img.shields.io/badge/Functional%20Testing-CRM%20Flows-4D96FF?style=flat-square)
![Regression Testing](https://img.shields.io/badge/Regression%20Testing-Build%20Validation-6BCB77?style=flat-square)
![UI Testing](https://img.shields.io/badge/UI%20Testing-Frontend%20Checks-F7B801?style=flat-square)
![Bug Reporting](https://img.shields.io/badge/Bug%20Reporting-Jira%20Style-9B5DE5?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-Data%20Validation-00BBF9?style=flat-square)
![Postman](https://img.shields.io/badge/Postman-API%20Testing-F15BB5?style=flat-square)
![Agile QA](https://img.shields.io/badge/Agile%20QA-Sprint%20Testing-00F5D4?style=flat-square)

</div>

---

## 🏆 Portfolio Value

This project demonstrates the ability to:

- Understand CRM business workflows.
- Create clear and reusable test documentation.
- Validate frontend usability and responsiveness.
- Identify functional, UI, data, and permission-related issues.
- Communicate bugs with proper severity, priority, and reproduction steps.
- Support release readiness through regression and test closure activities.

---

## 👤 Author

**Shashi Kant Singh**  
QA Tester | CRM Product Testing | Software Quality Assurance

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=gradient&customColorList=6,11,20,24,30" alt="Footer Banner" />

</div>
