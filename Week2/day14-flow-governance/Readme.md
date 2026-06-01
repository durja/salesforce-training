# Day 14 – Flow Governance & Approval Processes

## Multi-Level Approval Design

### 1. Course Creation Approval

**Approval Order:**

1. Faculty submits course proposal
2. Department Head reviews
3. Academic Dean approves
4. Registrar activates course

**After Approval:**

* Course is added to the course catalog.
* Students can register.

**After Rejection:**

* Proposal is returned to faculty with comments.

---

### 2. Faculty Leave Request

**Approval Order:**

1. Faculty submits leave request
2. Department Head reviews
3. Principal approves

**After Approval:**

* Leave is recorded in the system.
* Timetable adjustments are initiated.

**After Rejection:**

* Leave request is declined and faculty is notified.

---

### 3. Student Scholarship Request

**Approval Order:**

1. Student submits application
2. Scholarship Committee reviews
3. Finance Department verifies eligibility
4. Principal gives final approval

**After Approval:**

* Scholarship amount is allocated.

**After Rejection:**

* Student receives rejection notification.

---

### 4. Budget Approval

**Approval Order:**

1. Department submits budget request
2. Finance Manager reviews
3. Principal approves

**After Approval:**

* Budget is released for use.

**After Rejection:**

* Request is returned for revision.

---

## Branching Flow Logic

### Attendance Monitoring Flow

**Decision Point 1**

* If Attendance < 75%

  * Send warning email to student.

**Decision Point 2**

* If Attendance < 60%

  * Notify parents/guardians.

**Decision Point 3**

* If Attendance < 50%

  * Escalate case to administration.

### Actions Triggered

* Warning notifications
* Parent communication
* Administrative intervention
* Attendance tracking updates

---

## Governance Thinking

Enterprise systems cannot allow everyone to directly modify important records because:

* Protects sensitive data.
* Prevents unauthorized changes.
* Reduces human errors.
* Maintains accountability.
* Ensures approvals follow company policies.
* Minimizes financial and operational risks.
* Creates an audit trail for compliance.

---

## Reflection

Controlled workflows are necessary because they ensure consistency, accountability, and compliance with business policies.

Unrestricted actions may lead to:

* Incorrect decisions
* Data integrity issues
* Security breaches
* Financial losses
* Lack of accountability

Structured workflows provide transparency, auditability, and reliable business operations.
