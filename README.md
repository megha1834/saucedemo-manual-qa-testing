# SauceDemo Manual QA Testing Portfolio

A manual software QA project documenting test design, execution, and defect reporting for the [SauceDemo](https://www.saucedemo.com/) training application.

## Scope
- Login and logout
- Inventory browsing and sorting
- Shopping cart
- Checkout

## Artifacts
- [Test plan](docs/test-plan.md)
- [Test cases and execution tracker](test-cases/test-cases.csv) — 20 cases; **all initially Not Run**
- [Bug report template](bug-reports/BUG-TEMPLATE.md)
- [Test summary template](docs/test-summary.md)
- `evidence/` for screenshots (do not upload passwords or sensitive data)

## Execution instructions
1. Visit https://www.saucedemo.com/ and use the publicly provided demo credentials.
2. Open `test-cases/test-cases.csv` in Excel or Google Sheets.
3. Run each test from a clean, appropriate starting state; reset the app state when needed.
4. Fill in **Actual Result**, set **Status** to Pass, Fail, or Blocked, and add a relative screenshot path if useful.
5. For a genuine defect, create a separate report using the bug template and link the evidence.
6. Update the test summary with counts and known risks after testing.

**Integrity note:** Expected results describe intended behavior, not verified outcomes. No tests have been executed as part of this starter project. Do not claim a defect without reproducing it and confirming the expected requirement.

## Test design methods
Positive and negative testing, equivalence partitioning, decision-table coverage, functional and smoke testing.

## Tech and tools
Manual browser testing, CSV test tracking, Markdown documentation, Git and GitHub. Automation is planned as a separate follow-on project.
