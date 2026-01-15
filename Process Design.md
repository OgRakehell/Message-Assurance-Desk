# Process Design

The core of this project is the BPMN workflow that defines how OTP and SMS incidents are handled.

Key design principles:

- Data is retrieved once and reused across the process

- CSOs drive issue classification to improve accuracy and auditability

- External vendors are treated as service tasks, not manual steps

- Decision points are explicit and documented

The full BPMN diagram is available here:

![NotificationsPortal](/Assets/NotificationsPortal.png)

## Why BPMN

BPMN was chosen because it:

- Makes operational logic explicit and reviewable

- Separates process design from implementation tools

- Supports future execution in workflow engines

- Is easily understood by both technical and non-technical stakeholders

This ensures the process can evolve from concept to implementation without redesign.
