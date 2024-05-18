# Vacation Management System (VTS)

# Requirements:
## Vision:
The main goal of this application is to improve the internal business processes of this organization, at least concerning the time it takes to manage vacation time requests

## Function Requirements:
- Implements a flexible rules-based system for validating and verifying leave time requests
- Enables manager approval (optional)
- Provides access to requests for the previous calendar year, and allows requests to be made up to a year and a half in the future
- Uses e-mail notification to request manager approval and notify employees of request status changes
- Keeps activity logs for all transactions
- Enables the HR and system administration personnel to override all actions restricted by rules, with logging of those overrides
- Allows managers to directly award personal leave time (with system-set limits)
## Non Function Requirements:
- The system must be easy to use. (usability)
## Constraints:
- Uses existing hardware and middleware
- Is implemented as an extension to the existing intranet portal system, and uses the portal’s single-sign-on mechanisms for all authentication
# Domain:
The domain of the problem involves managing vacation time, sick leave, and personal time off for individual employees within an organization. It also encompasses streamlining HR processes related to time-off requests and approvals.

# Main Actors:
- Employee
- Manager
- Clerk (HR)
- System admin
# Entity Relationship Diagram:
[![Entity Relationship Diagram](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq/preview?elements=hUBPGotOQgHj_ZQ2dp8Wqg&type=embed)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq?elements=hUBPGotOQgHj_ZQ2dp8Wqg)



# Use Cases:
## Manage Time:
- **actor**: Employee, manager
- **goal**: the employee wishes to submit a new request for vacation time.
- **preconditions**: The employee is authenticated by the portal framework and identified as an employee of the company with privileges to manage his or her own vacation time.


### Employee flowchart and sequence diagram:
[![Manage time flowchart (employee)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq/preview?elements=KsHTCbtAvrMDcaUlLDk2KA&type=embed)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq?elements=KsHTCbtAvrMDcaUlLDk2KA)

[![Manage time Sequence Diagram (employee)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq/preview?elements=xlXp72UDPxXnxJ9uSieHLQ&type=embed)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq?elements=xlXp72UDPxXnxJ9uSieHLQ)

### Manager flowchart:
[![Manage time flowchart (manger)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq/preview?elements=3LfhPiLDw0AOFrWpUnJ07A&type=embed)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq?elements=3LfhPiLDw0AOFrWpUnJ07A)

## Withdraw request:
**actor**: Employee

**Goal: **The employee wants to withdraw an outstanding request for vacation time.

**Preconditions: **An employee has made a vacation time request, and that request has yet to be approved or denied by an authorized manager. See also main flow preconditions. (pending approval)

### Employee flowchart:
[![Withdraw request flowchart (employee)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq/preview?elements=hO-TOlpni6vDcqADToPSkg&type=embed)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq?elements=hO-TOlpni6vDcqADToPSkg)

## Cancel Approved Request:
**Actor**: Employee

**Goal: **The employee wants to cancel an approved vacation time request.

**Preconditions: **The employee has a vacation time request that has been approved and is scheduled for some time in the future or the recent past (pre-virus 5 business days)

### Employee flowchart:
[![Cancel Request flowchart (employee)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq/preview?elements=qILIUdvW0XJJaaaSnn4LGA&type=embed)](https://app.eraser.io/workspace/FhH051QWfH9KIzYcBeQq?elements=qILIUdvW0XJJaaaSnn4LGA)

## Edit Pending Request:
**Actor**: Employee

**Goal: **The employee wants to edit the description or title of a pending request.

**Preconditions: **An employee has made a vacation time request, and that request has yet to be approved or denied by an authorized manager.







## What if we need to have in the future another status like HR_Pending, HR_Approval with minimum change?
![Screenshot 2024-05-18 at 3.41.42 PM.png](https://eraser.imgix.net/workspaces/FhH051QWfH9KIzYcBeQq/lztSLAPBKZM6MF0hCaaXgJ99lMs2/pPYyxhG65nXWZbHBKUF1X.png?ixlib=js-3.7.0 "Screenshot 2024-05-18 at 3.41.42 PM.png")



