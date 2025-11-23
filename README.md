# Analysis-in-Software-Development
Example product backlog table (Markdown)
| ID   | Title                   | Description                        | Priority | Story Points | Status |
|------|-------------------------|------------------------------------|----------|--------------|--------|
| US01 | Create bank account     | Online sign-up + verification      | High     | 5            | To Do  |
| US02 | Customer login          | Secure login + 2FA                 | High     | 8            | To Do  |
| US03 | View balance            | Show available & ledger balance    | High     | 3            | To Do  |
| US04 | Transfer money          | Internal & external transfers      | High     | 8            | To Do  |
| ...  | ...                     | ...                                | ...      | ...          | ...    |


### US01 — Create Bank Account
**As a** new customer  
**I want** to create an online bank account  
**So that** I can access banking services

**Acceptance Criteria**
- Given I have valid national ID, when I submit registration form, then account is created.
- Email or phone verification required before first login.
- System generates a unique account number.
- Error message shown for duplicate national ID.

**Priority:** High  
**Story Points:** 5
