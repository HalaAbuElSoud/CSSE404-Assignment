## Threat Analysis Summary
The STRIDE threat modelling approach identified two primary risks to the Smart Waste Management System: **tampering** and **elevation of privilege**.

**Tampering** was identified in components such as IoT Bins and the Cloud Database, where attackers might try to change firmware or corrupt stored data. To protect against unauthorised modifications, the system implements **firmware integrity checks** and **secure write operations** in the cloud.

**Elevation of Privilege** risks were identified, notably at access points like the  Admin Dashboard. These dangers emphasise the potential of unauthorised persons getting administrative access. As a countermeasure, the system employs **position-Based Access Control (RBAC)**, which limits each user to the rights necessary for their position and protects sensitive functions through higher authentication requirements.

Together, these mitigations improve the system's security posture by assuring data integrity and restricting access.
