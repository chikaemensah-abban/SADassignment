Patient Care User Stories

User Story 1: Book an Appointment

As a patient
I want to book an appointment with a doctor
So that I can receive medical care at a suitable time.

Acceptance Criteria

Scenario: Patient books an available appointment

Given a patient is registered in the healthcare system
And a doctor has an available appointment slot
When the patient selects the available slot and confirms the booking
Then the system should create the appointment
And display the appointment details to the patient



User Story 2: Update Personal Information

As a patient
I want to update my personal information
So that my patient records contain accurate contact details.

Acceptance Criteria

Scenario: Patient updates their contact information

Given a patient is registered in the healthcare system
When the patient updates their contact information and saves the changes
Then the system should update the patient's information
And display a confirmation message to the patient