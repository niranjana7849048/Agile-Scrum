# Sprint Plan – Airline Web Check-in

## 1. Sprint Overview

| Detail | Value |
|---|---|
| Project | Airline Web Check-in |
| Team Size | 6 Members |
| Sprint Duration | 8 Working Days |
| Focus Factor | 70% |

## 2. Team Capacity Calculation

Assumption: Each team member works 8 hours per day.

Total Available Hours = 6 × 8 × 8 = 384 hours

Effective Capacity = 384 × 70% = 268.8 hours

Effective Capacity ≈ 269 hours.

For illustrative planning, assume 1 story point represents approximately 6 hours of effort. This is not a universal Scrum conversion.

Estimated Capacity = 269 / 6 = 44.83 story points.

The team plans 33 story points, allowing a buffer for dependencies and unexpected work.

## 3. Sample Product Backlog

The assignment's referenced backlog was not provided. The following is illustrative sample data.

| Story ID | User Story | Story Points | Priority | Selection |
|---|---|---:|---|---|
| US01 | Search booking using PNR and surname | 5 | High | Selected |
| US02 | Retrieve passenger booking details | 5 | High | Selected |
| US03 | Select an available seat | 8 | High | Selected |
| US04 | Display boarding pass | 5 | High | Selected |
| US05 | Validate passenger check-in eligibility | 5 | High | Selected |
| US06 | Pay for seat upgrades through payment gateway | 8 | Medium | Not Selected |
| US07 | Send check-in confirmation email | 5 | Medium | Selected |
| US08 | Download baggage information | 3 | Low | Not Selected |

## 4. Selected Stories

| Story ID | User Story | Story Points |
|---|---|---:|
| US01 | Search booking | 5 |
| US02 | Retrieve passenger details | 5 |
| US03 | Select an available seat | 8 |
| US04 | Display boarding pass | 5 |
| US05 | Validate check-in eligibility | 5 |
| US07 | Send confirmation email | 5 |
| | **Total** | **33** |

## 5. Sprint Goal

Enable passengers to retrieve booking details, validate check-in eligibility, select available seats, view their boarding pass, and receive check-in confirmation.

## 6. Dependency Management

The payment-gateway sandbox is unavailable.

- Exclude the seat-upgrade payment story from this sprint.
- Scrum Master coordinates with the payment gateway provider.
- Developers continue working on unblocked stories.
- Reconsider the payment story after sandbox access is restored.

## 7. Sprint Commitment

The team commits to 33 story points for the 8-working-day sprint, subject to ongoing progress and any negotiated scope changes.

## 8. Conclusion

The team plans the core airline check-in workflow within its estimated capacity while managing the external payment-gateway dependency.