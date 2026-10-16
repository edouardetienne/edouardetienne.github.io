# Smoke tests

- **Shallow** - check the function is present and broadly accessible
- **Wide** - covers the most critical features across the entire application
- **Focused on critical paths** - tests only the happy paths of the most essential features under normal confitions

At the very beginning of the testing workflowe

## Smoke testing vs deep execution
- Purpose: Is the build stable?
- Scope: The presence of the expected pages in the website.
- Focus: Critical paths for the various test suites are the presence of the relevant pages in the website.
- Execution: Manual tests performed before merging into the main branch. They should take only a few minutes.
- Outcome: The pull request towards the portfolio cannot be accepted if the smoke tests are not passed.

