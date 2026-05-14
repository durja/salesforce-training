# 🚀 Salesforce Summer Program – Day 6 Triggers & SOQL

---

# 📖 What is SOQL?
SOQL (Salesforce Object Query Language) is used to retrieve data from Salesforce objects and records.

It helps users search, filter, and access data stored in Salesforce.

---

# 📖 What is an Apex Trigger?
An Apex Trigger is code that runs automatically when records are created, updated, deleted, or restored in Salesforce.

Triggers help automate business actions based on data changes.

---

# 🔄 Difference Between Flow and Trigger

## Flow
- No-code automation
- Easier to build
- Used for simple automation

Examples:
- Email notifications
- Updating records

---

## Trigger
- Code-based automation
- Used for complex business logic
- More flexibility and control

Examples:
- Complex validations
- Advanced automation

---

# 🔄 Before vs After Trigger

## Before Trigger
Runs before data is saved to the database.

Example:
- Validate student information before saving

## After Trigger
Runs after data is saved.

Example:
- Send confirmation email after registration

---

# 💡 Trigger Use Cases – College Management System

## 1. Student Registration
After student registration → send welcome email.

## 2. Course Full Notification
After course becomes full → notify faculty.

## 3. Attendance Warning
After attendance drops below 75% → send warning.

## 4. Fee Payment
After fee payment → update payment status.

## 5. Course Enrollment
After enrollment → reduce remaining seats automatically.

---

# ⚙️ Flow vs Trigger Thinking

## Simple Email Notification
Use Flow because it is simple automation.

## Complex Fee Eligibility Check
Use Apex Trigger because logic is complex.

## Updating Related Records
Use Flow for simple updates.

## External API Integration
Use Apex Trigger for advanced integration logic.

---

# 🔍 Query Examples

- Find all students in Course A
- Find all courses handled by Faculty X
- Find students with attendance below 75%
- Find students who did not pay fees
- Find courses with available seats

---
