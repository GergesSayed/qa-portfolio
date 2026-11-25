# QA Portfolio Sample: Swag Labs (saucedemo.com)

**This is a self-made practice sample. It is not professional work and not from a past job.**

I am Girgis Saied, an IT specialist moving into software testing. I studied the ISTQB Foundation syllabus (I have not taken the exam). To practise, I wrote test cases and a bug report for a public demo shop that exists for testers: https://www.saucedemo.com

Tested manually in Chrome on 25 November 2026.

## What is in this repo

| File | What it is |
| --- | --- |
| `QA_Test_Cases_SauceDemo.xlsx` | 15 test cases with steps, expected result, actual result and status. A Summary sheet lists scope and notes. |
| `BUG-001.md` | One bug report: steps to reproduce, expected vs actual, severity, impact and a screenshot. |
| `QA_Bug_Report_BUG-001.pdf` | The same bug report as a PDF. |
| `BUG-001_screenshot.jpg` | Screenshot of the bug (small, compressed). |

## Results

- 15 test cases run: 14 passed, 1 failed.
- 1 bug reported (BUG-001): logged in as `problem_user`, all 6 products show the same image.
- `problem_user` is an account the site's makers built with defects on purpose, so this bug is a known practice defect. I include it to show how I write a bug report.

## Scope

Covered: login (valid, empty fields, wrong password, locked-out user), product list, image check, sorting, cart, checkout (required fields, total calculation, order completion).

Not covered: menu and social links, the other special demo users (performance_glitch_user, error_user, visual_user), mobile layouts, automation.

## Test data

Public demo credentials shown on the site's login page: `standard_user`, `problem_user`, `locked_out_user`, password `secret_sauce`.

## Contact

Girgis Saied: gergessayed@gmail.com
