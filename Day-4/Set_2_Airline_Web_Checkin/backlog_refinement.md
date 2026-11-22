# Backlog Refinement – Airline Web Check-in

## 1. Objective

Backlog refinement is used to clarify requirements, split oversized stories, identify dependencies, and estimate upcoming work.

The team prepares the top five stories for the next sprint.

## 2. Prioritised Product Backlog – Next Sprint

The following estimates are illustrative planning estimates.

| Priority | Story ID | User Story | Story Points |
|---|---|---|---:|
| 1 | US06 | Pay for seat upgrades through payment gateway | 8 |
| 2 | US08 | Download baggage information | 3 |
| 3 | US09 | Modify selected seat before check-in confirmation | 5 |
| 4 | US10 | Cancel check-in before departure | 8 |
| 5 | US11 | Receive check-in status notifications | 5 |

## 3. Splitting an Oversized Story

Original Story:

**US06 – Seat Upgrade Payment**

As a passenger, I want to pay for a seat upgrade so that I can confirm my preferred seat.

This story is split into smaller stories to make implementation and testing easier.

| New Story ID | User Story | Description | Story Points |
|---|---|---|---:|
| US06A | View seat-upgrade price | Display the price of the selected upgraded seat. | 3 |
| US06B | Initiate seat-upgrade payment | Send the payment request to the payment gateway. | 3 |
| US06C | Confirm successful payment | Confirm payment and update the booking. | 5 |
| US06D | Handle payment failure | Display failure details and allow retry where appropriate. | 3 |

## 4. Re-estimation

| Story | Original Estimate | Revised Estimate |
|---|---:|---:|
| US06 – Seat Upgrade Payment | 8 SP | 14 SP total across four smaller stories |

The revised total is not necessarily a reduction in effort. Splitting makes the work easier to understand, estimate, implement, and test.

## 5. Refinement Activities

1. Review business requirements with the Product Owner.
2. Clarify acceptance criteria for each story.
3. Identify external dependencies.
4. Split large stories into smaller pieces.
5. Estimate the refined stories using the team's estimation approach.
6. Reorder the Product Backlog according to business priority.

## 6. Conclusion

Backlog refinement improves clarity and helps the team prepare stories for future sprint planning.

The payment-gateway story should be selected only after the sandbox dependency and required acceptance criteria are addressed.