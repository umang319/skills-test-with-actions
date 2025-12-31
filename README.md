# GitHub Actions – Continuous Integration Demo

This repository was created as part of the official **GitHub Skills: Test with Actions** learning course.

The goal was to learn the fundamentals of CI/CD automation using GitHub Actions by implementing a real CI workflow.

---

## What Was Implemented

### ✓ Continuous Integration Workflow
- Configured a GitHub Actions CI pipeline triggered on Pull Requests
- Automated Markdown linting to enforce formatting standards

### ✓ Test Execution & Fixing Errors
- Analyzed failed CI logs to locate issues
- Corrected Markdown rule violations to ensure tests pass

### ✓ Build Artifacts for Test Reports
- Generated structured lint reports (`remark-lint-report.json`)
- Uploaded reports as CI artifacts for review

### ✓ Branch Protection Rules
- Required pull request workflow to pass before merging
- Helped ensure stable, error-free code reaches main branch

### ✓ Successful Protected Merge
- Pull Request merged into `main` **only after CI passed**
- Demonstrated real-world gated CI approvals workflow

---

## GitHub Actions Workflow File
Workflow located at:
