# Impediment Log – Airline Web Check-in

## 1. Sprint Details

| Detail | Value |
|---|---|
| Project | Airline Web Check-in |
| Team Size | 6 Members |
| Sprint Duration | 8 Working Days |
| Main Impediment | Payment-gateway sandbox unavailable |

## 2. Impediment Register

| ID | Impediment | Impact | Owner | Expected Resolution | Status |
|---|---|---|---|---|---|
| IMP01 | Payment-gateway sandbox is unavailable. | Blocks implementation testing of seat-upgrade payment integration. | Payment Integration Developer | Within 2 working days (target) | Open |
| IMP02 | Sandbox credentials are not accessible to the team. | Prevents developers from validating payment requests and responses. | Technical Lead | After sandbox access is restored | Open |
| IMP03 | Seat-upgrade payment integration depends on external gateway services. | May delay the seat-upgrade feature. | Scrum Master | Follow up with gateway provider | Open |

## 3. Impact Analysis

- Seat-upgrade payment integration cannot be fully tested.
- Developers may be unable to validate payment success and failure responses.
- The sprint goal should remain achievable without this blocked feature.
- The team must avoid treating an untested payment integration as completed work.

## 4. Scrum Master's Impediment Removal Actions

| Step | Action |
|---|---|
| 1 | Record the unavailable sandbox as an impediment. |
| 2 | Contact the payment-gateway support team. |
| 3 | Escalate the issue to the technical lead and relevant vendor contact. |
| 4 | Request sandbox access and valid test credentials. |
| 5 | Follow up on the expected resolution date. |
| 6 | Inform the Developers when access is restored. |
| 7 | Review whether the blocked story can be considered in future sprint planning. |

## 5. Escalation Path

Developer → Scrum Master → Technical Lead → Payment Gateway Support / Vendor

The Scrum Master coordinates the escalation and helps remove organizational blockers.

## 6. Conclusion

The payment-gateway sandbox dependency is a significant impediment to seat-upgrade payment testing.

The Scrum Master should coordinate with the external provider and technical team to resolve the issue. The Developers should continue working on other sprint backlog items that are not blocked by this dependency.