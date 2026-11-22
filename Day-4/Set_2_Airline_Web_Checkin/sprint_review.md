# Sprint Review – Airline Web Check-in

## 1. Sprint Review Details

| Detail | Value |
|---|---|
| Project | Airline Web Check-in |
| Sprint Duration | 8 Working Days |
| Participants | Product Owner, Scrum Team, Stakeholders |
| Meeting | Sprint Review |

## 2. Sprint Review Agenda

| No. | Agenda Item | Description |
|---|---|---|
| 1 | Welcome and Introduction | Explain the sprint goal and review purpose. |
| 2 | Sprint Goal Review | Check whether the sprint goal was achieved. |
| 3 | Product Demonstration | Demonstrate completed check-in features. |
| 4 | Acceptance Criteria Verification | Verify completed stories against acceptance criteria. |
| 5 | Stakeholder Feedback | Collect feedback and suggestions. |
| 6 | Backlog Discussion | Discuss new requirements and priority changes. |
| 7 | Conclusion | Summarise outcomes and next steps. |

## 3. Demonstration Script

### US01 – Search Booking

**Acceptance Criteria:**
- Passenger can enter a valid PNR.
- Passenger can enter the registered surname.
- System retrieves the matching booking.
- Invalid details display an appropriate error.

**Demo Steps:**
1. Open the check-in page.
2. Enter a valid PNR and surname.
3. Click Search.
4. Verify booking details are displayed.
5. Enter invalid details and verify the error message.

### US02 – Retrieve Passenger Details

**Acceptance Criteria:**
- System displays passenger details for a valid booking.
- Booking information is retrieved correctly.
- Invalid booking requests are handled appropriately.

**Demo Steps:**
1. Search using a valid booking.
2. Display passenger information.
3. Verify the retrieved booking details.

### US03 – Select an Available Seat

**Acceptance Criteria:**
- Available seats are displayed.
- Passenger can select an available seat.
- Unavailable seats cannot be selected.
- The selected seat is reflected in the booking.

**Demo Steps:**
1. Open the seat selection page.
2. Display available and unavailable seats.
3. Select an available seat.
4. Verify that the selection is saved.

### US04 – Display Boarding Pass

**Acceptance Criteria:**
- Boarding pass displays passenger details.
- Flight number and seat number are displayed.
- Boarding pass is available after successful check-in.

**Demo Steps:**
1. Complete the check-in flow.
2. Open the boarding pass.
3. Verify passenger and flight details.

### US05 – Validate Check-in Eligibility

**Acceptance Criteria:**
- Eligible passengers can proceed with check-in.
- Ineligible passengers receive an appropriate message.
- Invalid or incomplete booking information is handled.

**Demo Steps:**
1. Open a valid eligible booking.
2. Verify that check-in is permitted.
3. Test an ineligible booking.
4. Verify the displayed message.

### US07 – Send Check-in Confirmation Email

**Acceptance Criteria:**
- Confirmation email is triggered after successful check-in.
- Email contains relevant booking information.
- Email delivery failures are handled appropriately.

**Demo Steps:**
1. Complete the check-in process.
2. Trigger the confirmation email.
3. Verify the email content and delivery result.

## 4. Blocked Feature Discussion

### US06 – Seat Upgrade Payment

The payment-gateway sandbox was unavailable during the sprint.

- Payment integration could not be fully validated.
- The feature must not be presented as completed.
- The dependency is recorded in the impediment log.
- The story will be reconsidered after sandbox access is restored.

## 5. Stakeholder Feedback

| Stakeholder Feedback | Follow-up Action |
|---|---|
| Improve clarity of seat availability. | Review seat-selection screen. |
| Provide clear messages for ineligible passengers. | Improve validation messages. |
| Confirm payment integration reliability. | Test payment flow after sandbox access is restored. |

## 6. Sprint Review Outcome

The team demonstrates completed functionality and collects stakeholder feedback.

The Product Owner reviews the feedback and updates the Product Backlog where necessary.

The Sprint Review is used to inspect the product increment and determine future adaptations.

**Note:** This is a review agenda and demonstration script. Actual completion results and stakeholder feedback should be updated after the sprint.