# Definition of Ready – Airline Web Check-in

## 1. Introduction

Definition of Ready (DoR) is a checklist used by the Scrum team to confirm that a user story is sufficiently clear and prepared before it is selected for a sprint.

## 2. Definition of Ready Checklist

A story is considered Ready when:

- User story is clearly written.
- Business requirements are understood.
- Acceptance criteria are defined.
- Dependencies are identified.
- Required designs or API details are available.
- The story is estimated by the Developers.
- The story is small enough to complete within the sprint.

## 3. Story-wise Readiness Assessment

| Story ID | User Story | Clear Requirement | Acceptance Criteria | Dependencies Checked | Estimated | Ready Status |
|---|---|---|---|---|---|---|
| US01 | Search booking using PNR and surname | Yes | Yes | Yes | 5 SP | Ready |
| US02 | Retrieve passenger booking details | Yes | Yes | Yes | 5 SP | Ready |
| US03 | Select an available seat | Yes | Yes | Yes | 8 SP | Ready |
| US04 | Display boarding pass | Yes | Yes | Yes | 5 SP | Ready |
| US05 | Validate passenger check-in eligibility | Yes | Yes | Yes | 5 SP | Ready |
| US07 | Send check-in confirmation email | Yes | Yes | Yes | 5 SP | Ready |

## 4. Blocked Story Assessment

| Story ID | User Story | Missing Requirement | Readiness |
|---|---|---|---|
| US06 | Pay for seat upgrades through payment gateway | Payment-gateway sandbox is unavailable | Not Ready |

US06 cannot be considered Ready because the team cannot properly validate the payment integration without the sandbox.

## 5. Conclusion

The Definition of Ready helps prevent unclear requirements and unresolved dependencies from entering sprint execution.

The team should refine US06 and confirm sandbox availability before selecting it for a future sprint.