# OpenCart E-Commerce Manual Testing Portfolio

A complete end-to-end manual testing project on the OpenCart demo e-commerce application, covering 8 functional modules, 33 test cases, and 4 documented bugs with full evidence.

---

## Project Overview

- **Application Under Test:** OpenCart Demo — demo.opencart.com
- **Testing Type:** Functional Manual Testing
- **Environment:** Chrome Browser, macOS
- **Test Period:** 27-May-2026 to 28-May-2026
- **Total Test Cases:** 33
- **Pass Rate:** 88% (29 Passed / 4 Failed)
- **Bugs Reported:** 4 (3 High, 1 Medium)

---

## Modules Tested

- Registration — 4 TCs — 3 Pass, 1 Fail — 75%
- Login — 4 TCs — 3 Pass, 1 Fail — 75%
- Search — 5 TCs — 5 Pass, 0 Fail — 100%
- Product Page — 4 TCs — 3 Pass, 1 Fail — 75%
- Cart — 5 TCs — 5 Pass, 0 Fail — 100%
- Checkout — 4 TCs — 3 Pass, 1 Fail — 75%
- My Account — 5 TCs — 5 Pass, 0 Fail — 100%
- Logout — 2 TCs — 2 Pass, 0 Fail — 100%
- **Total — 33 TCs — 29 Pass, 4 Fail — 88%**

---

## Bugs Found

- **BUG_001** — Registration — Confirm password field missing — Severity: Medium — Status: Open
- **BUG_002** — Login — Password reset completed without email verification — Severity: High — Status: Open
- **BUG_003** — Product Page — Add to Cart accepts quantity 0 and -1 — Severity: High — Status: Open
- **BUG_004** — Checkout — Checkout silently blocked with no error message — Severity: High — Status: Open

---

## Project Files

- **Manual_Testing_Project_OpenCart.xlsx** — Complete test documentation with all 6 tabs
- **Screenshots/** — All test evidence screenshots

### What Is Inside the Excel File

- Tab 1 — Test Plan — Scope, objectives, strategy, schedule, resources
- Tab 2 — Test Cases and Execution — 33 test cases with steps, expected results, actual results, pass/fail
- Tab 3 — Bug Report — 4 bugs with title, severity, steps to reproduce, expected vs actual
- Tab 4 — RTM — Requirements Traceability Matrix mapping 33 requirements to test cases and results
- Tab 5 — Execution Log — Test execution log with date, tester, and status per test case
- Tab 6 — Test Summary Report — Module results, bug severity breakdown, risks, observations, sign-off

---

## Test Scenarios Covered

### Registration
- Valid user registration with all required fields
- Mandatory field validation on empty form submission
- Duplicate email rejection
- Password and confirm password mismatch validation

### Login
- Login with valid credentials
- Login with invalid password
- Login with unregistered email
- Forgotten password flow

### Search
- Search with exact product name
- Search with partial keyword
- Case-insensitive search
- Empty search submission
- Special characters in search field

### Product Page
- Product detail display name, price, description, image
- Invalid quantity entry  letters and symbols
- Zero and negative quantity validation
- Add to Cart functionality

### Cart
- Cart displays correct product, quantity, and price
- Quantity update and total recalculation
- Cart total updates correctly after quantity change
- Remove product from cart
- Empty cart state message

### Checkout
- Complete checkout with valid billing and shipping details
- Out-of-stock item handling
- Order summary matches cart items before placing order
- Order confirmation page after successful order

### My Account
- Update account information — first name and last name
- Change password successfully and login with new password
- View order history with past orders
- Address book management
- Wish list management

### Logout
- Logout redirects to Account Logout confirmation page
- Accessing account URL after logout redirects to Login page

---

## Risks and Observations

- **Risk 1** — Cart total recalculation bug may impact revenue calculation — High priority fix needed
- **Risk 2** — Empty search UX issue — users receive no guidance on search page
- **Risk 3** — Quantity field validation gap allows zero and negative cart additions
- **Risk 4** — Tested only on demo environment — behavior may differ on production server

---

## Sign-Off

**Test Result: FAIL — Not Recommended for Production Release**

3 High severity bugs remain open (BUG_002, BUG_003, BUG_004). Re-testing required after developer fixes. Application passes 88% of test cases and is stable for standard happy-path flows across Search, Cart, My Account, and Logout modules.

---

## Skills Demonstrated

- Manual test case design and execution
- Bug identification, documentation, and severity classification
- Requirements Traceability Matrix (RTM) creation
- Test summary reporting and QA sign-off
- Functional testing across end-to-end e-commerce user journeys
- Test evidence collection with screenshots

---

## About

This project was created as a manual testing portfolio to demonstrate hands-on QA skills on a real-world e-commerce application. The OpenCart demo application was used as the system under test, covering the complete user journey from registration to order placement and account management.
