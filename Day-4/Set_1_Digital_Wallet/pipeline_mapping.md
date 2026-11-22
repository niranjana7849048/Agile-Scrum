# Definition of Done Mapping to Build Pipeline

## 1. Introduction

The Definition of Done (DoD) describes the quality requirements that a product increment must satisfy before it can be considered complete.

A build pipeline helps automate and verify these requirements.

## 2. DoD and Pipeline Mapping

| DoD Requirement | Pipeline Stage | Description |
|---|---|---|
| Build successfully | Build | Compile the application and identify build errors. |
| Unit tests pass | Test | Execute automated unit tests to verify individual components. |
| Code review completed | Code Review | Ensure changes are reviewed and approved by another developer. |
| Code merged | Merge | Merge approved changes into the main development branch. |
| Documentation updated | Documentation Check | Verify that relevant documentation is maintained. |

## 3. Pipeline Workflow

1. Developer completes a code change.
2. Developer pushes the changes to the version-control repository.
3. The pipeline starts the build process.
4. Automated unit tests are executed.
5. Code review is completed.
6. Approved changes are merged into the main branch.
7. The team verifies that the completed increment meets the Definition of Done.

## 4. Benefits of Pipeline Automation

- Detects build failures early.
- Reduces manual testing effort.
- Improves code quality.
- Helps identify integration problems.
- Ensures consistent quality checks.
- Supports reliable and frequent software delivery.

## 5. Conclusion

Mapping the Definition of Done to the build pipeline ensures that every completed user story meets agreed quality standards.

Automated builds and tests, combined with code review and controlled merging, help the Scrum team deliver a potentially releasable product increment.