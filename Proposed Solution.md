### Proposed Solution

The proposed solution is a workflow-based notifications portal driven by a BPMN-defined process.

At a high level, the process:

- Accepts a customer account number as input

- Retrieves OTP and SMS phone numbers from the core banking system

- Allows the CSO to select the reported issue type

- Queries the relevant database for status for the business 

- Queries the relevant delivery vendors for status

- Determines next actions based on delivery outcomes

- Guides customer feedback or vendor escalation in a consistent manner

All investigations follow the same logical flow, ensuring consistency and traceability.
