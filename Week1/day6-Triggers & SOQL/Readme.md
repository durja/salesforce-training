# 🚀 Salesforce Summer Program – Day 6 Triggers & SOQL

---

# 📖 What is SOQL?
SOQL is used to retrieve data from Salesforce objects and records.

It helps users search and access data stored in Salesforce.

---

# 📖 What is an Apex Trigger?
An Apex Trigger is code that runs automatically when records are created, updated, or deleted.

It helps automate actions based on data changes.

---

# 🔄 Flow vs Trigger

## Flow
- No-code automation
- Used for simple tasks

Examples:
- Email notifications
- Updating records

## Trigger
- Code-based automation
- Used for complex logic

Examples:
- Complex validations
- Advanced automation

---

# 🔄 Before vs After Trigger

## Before Trigger
Runs before saving data.

Example:
- Validate student details

## After Trigger
Runs after saving data.

Example:
- Send welcome email

---

# 💡 Trigger Use Cases – College Management System

1. After student registration → send welcome email  
2. After course becomes full → notify faculty  
3. After attendance drops below 75% → send warning  
4. After fee payment → update payment status  
5. After enrollment → reduce remaining seats  

---

# ⚙️ Flow vs Trigger Thinking

- Simple email notification → Flow  
- Complex fee eligibility check → Trigger  
- Updating related records → Flow  
- External API integration → Trigger  

---

# 🔍 Query Examples

- Find all students in Course A  
- Find all courses handled by Faculty X  
- Find students with attendance below 75%  
- Find students who did not pay fees  
- Find courses with available seats  
