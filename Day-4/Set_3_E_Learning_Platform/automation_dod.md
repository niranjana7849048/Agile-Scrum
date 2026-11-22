# Automation Supporting Definition of Done – E-Learning Platform

## 1. Introduction

Automation helps the Scrum team maintain software quality and ensure that completed user stories satisfy the Definition of Done (DoD).

Automated unit tests, linting, and CI/CD pipelines help identify errors early and reduce manual effort.

## 2. Automation Activities and DoD Mapping

| Automation Activity | Description | Definition of Done Contribution |
|---|---|---|
| Unit Testing | Automatically tests individual functions and components. | Ensures individual components work correctly. |
| Code Linting | Checks source code for style issues and common errors. | Maintains consistent and readable code. |
| Build Automation | Automatically builds the application after code changes. | Confirms that the application builds successfully. |
| Integration Testing | Tests interactions between application modules and APIs. | Verifies that integrated components work together. |
| Code Review | Developers review code changes before merging. | Improves code quality and catches issues. |
| CI/CD Pipeline | Runs automated quality checks whenever code is pushed. | Ensures consistent validation before merging and delivery. |

## 3. Example CI/CD Pipeline Workflow

1. Developer writes and commits code.
2. Code is pushed to the version-control repository.
3. The CI pipeline starts automatically.
4. The application build is executed.
5. Automated unit tests are run.
6. Linting checks are performed.
7. Integration tests are executed where configured.
8. Code review and approval are completed.
9. Approved changes are merged into the main branch.
10. The application is deployed when the required pipeline checks and approvals are satisfied.

## 4. How Automation Supports DoD

### Unit Tests
- Verify individual functions and components.
- Detect defects early.
- Prevent regressions.

### Linting
- Identifies coding style violations.
- Detects common code quality issues.
- Encourages consistent coding practices.

### Build Pipeline
- Automatically verifies that the application builds.
- Runs configured tests and quality checks.
- Prevents changes from progressing when required checks fail.

### Code Review and Merge
- Ensures changes are reviewed.
- Maintains code quality.
- Ensures only approved changes are merged.

## 5. Benefits of Automation

- Reduces repetitive manual testing.
- Detects defects earlier.
- Improves software reliability.
- Maintains consistent coding standards.
- Speeds up development and integration.
- Supports frequent and reliable software delivery.

## 6. Conclusion

Automation supports the Definition of Done by verifying software quality through unit tests, linting, builds, integration tests, and code reviews.

A properly configured CI/CD pipeline helps the team ensure that completed work meets agreed quality standards before it is merged and delivered.