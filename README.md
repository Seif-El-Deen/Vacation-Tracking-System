# Vacation Tracking System

## Domain
In many companyies it's a time consuming process for an employee to request a vacation in a manual way, be applying a written request for his vacation request to the hr, then waiting for a couple of days until the hr asks for the manager's approval.

## Vision
The individual employees can manage their own vacation time, sick leave, and personal time off without needing to be experts in company policy.

## Functional
- Implements a flexible rules-based system for validating and verifying leave time requests. This system replaces the manual checks previously done by the HR department.
- Enables manager approval (optional) for leave requests.
- Provides access to requests for the previous calendar year.
- Allows requests to be made up to a year and a half in the future.
- Uses e-mail notification to request manager approval and notify employees of request status changes.
- Keeps activity logs for all transactions (Auditing).
- Enables HR and system administration personnel to override all actions restricted by rules, with logging of those overrides.
- Allows managers to directly award personal leave time (comp time), subject to system-set limits.
- Provides a Web service interface for other internal systems to query any given employee’s vacation request summary.
- Interfaces with the HR department legacy systems to retrieve required employee information and changes.

## Non Functional Requirements
- Usability and Ease of Use
- Performance
- Security
- Compatibility and Environment Constraints
- Scalability
- Maintainability and Manageability (specifically for HR and Admin).

## Constraints
- Intranet Portal Extension (Integration with Existing Systems).
- Web Application Architecture
- Single Sign-On.
- Use of Existing Infrastructure.
- Rules-Based Validation.
- Browser Compatibility.
- System-Set Limits on Manager Awarded Time.

## Domain
If an employee wants to ask/requests a vacation, this process is made manually and it may take too long time and it is totally dependent on humans.

## Actors of the System
- Employee
- Manager
- Clerk (Hr)
- System Admin

## ERD
![VTS ERD!](https://raw.githubusercontent.com/Seif-El-Deen/Vacation-Tracking-System/refs/heads/main/Diagram/VTS%20ERD.png)

## Manage Time (Use Case):
- ### Flowchart:
![Manage Time Flowchart!](https://raw.githubusercontent.com/Seif-El-Deen/Vacation-Tracking-System/refs/heads/main/Diagram/Flowchart%20Manage%20Time.png)

- ### Sequence Diagram:
- ![VTS Flowchart!](https://raw.githubusercontent.com/Seif-El-Deen/Vacation-Tracking-System/refs/heads/main/Diagram/Manage%20Time(Employee)%20Sequence%20Diagram.png)



## Withdraw Request (Use Case):
- ### Flowchart:
![Withdraw Request Flowchart!](https://raw.githubusercontent.com/Seif-El-Deen/Vacation-Tracking-System/refs/heads/main/Diagram/Flowchart%20Withdraw%20Request.png)

