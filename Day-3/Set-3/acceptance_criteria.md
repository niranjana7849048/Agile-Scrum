
# Acceptance Criteria – Hospital Appointment Booking Application

## 1. Book an Appointment

**Scenario: Successful appointment booking**

- Given the patient has selected an available doctor and time slot
- When the patient confirms the appointment
- Then the system should book the appointment and display a confirmation message

**Negative Scenario: Appointment slot already taken**

- Given the patient has selected an appointment slot
- When another patient books that slot before confirmation
- Then the system should display a message that the slot is no longer available and ask the patient to select another slot

## 2. View Booked Appointments

**Scenario: View appointment details**

- Given the patient has successfully booked an appointment
- When the patient opens the booked appointments section
- Then the system should display the appointment date, time and doctor details

## 3. Reschedule an Appointment

**Scenario: Successful rescheduling**

- Given the patient has an existing appointment
- When the patient selects another available slot and confirms the change
- Then the system should update the appointment with the new date and time

**Negative Scenario: Selected slot unavailable**

- Given the patient is rescheduling an appointment
- When the patient selects a slot that is no longer available
- Then the system should display an error message and ask the patient to choose another slot

## 4. Cancel an Appointment

**Scenario: Successful cancellation**

- Given the patient has an existing appointment
- When the patient confirms the cancellation
- Then the system should cancel the appointment and make the slot available for other patients

**Negative Scenario: Appointment already cancelled**

- Given the appointment has already been cancelled
- When the patient attempts to cancel it again
- Then the system should display a message indicating that the appointment is already cancelled

## Conclusion

Acceptance criteria define the expected behaviour of booking, rescheduling and cancellation features and help verify that the application works correctly.
