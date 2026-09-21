Domain Context Mapping

Context Diagram

flowchart LR
    PM[Patient Management]
    HCP[Healthcare Portal]
    BC[Billing & Insurance Claims]
    LTD[Lab Test Diagnostics]

    PM --> HCP
    HCP --> BC
    HCP --> LTD

Primary Entities

Patient Management

- Patient
- Doctor
- Appointment
- Medical Record

Billing & Insurance Claims

- Invoice
- Payment
- Insurance Policy
- Insurance Claim

Lab Test Diagnostics

- Lab Test
- Test Order
- Sample
- Test Result