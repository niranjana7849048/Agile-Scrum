
# Acceptance Criteria – Insurance Claims Portal

## 1. Enter Policy Details

**Scenario: Valid policy details**

- Given the customer is on the claim registration page
- When the customer enters a valid policy number
- Then the portal should accept the policy details and allow the customer to continue

## 2. Provide Incident Details

**Scenario: Submit incident information**

- Given the customer has entered valid policy details
- When the customer provides the incident date and description
- Then the portal should save the incident details

**Negative Scenario: Missing incident details**

- Given the customer is on the incident details page
- When the customer submits the form without entering the required incident details
- Then the portal should display a validation error message

## 3. Submit Claim

**Scenario: Successful claim submission**

- Given the customer has entered valid policy and incident details
- When the customer submits the claim
- Then the portal should register the claim and generate a claim reference number

**Negative Scenario: Invalid policy number**

- Given the customer enters an invalid policy number
- When the customer attempts to submit the claim
- Then the portal should display an invalid policy validation message and prevent submission

## Conclusion

Acceptance criteria define the expected behaviour of each claim registration feature and help verify that the requirements are satisfied.
