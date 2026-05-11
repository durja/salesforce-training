# 🚀 Salesforce Summer Program – Day 3 Data Modeling

---

# 📖 Difference Between Concepts

## App
A collection of related tabs and objects used for a business process.

## Object
A database table used to store data.

## Record
A single row of data inside an object.

## Field
Stores specific information inside a record.

---

# Standard vs Custom Objects

## Standard Objects
Objects already provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity

## Custom Objects
Objects created based on business needs.

Examples:
- Student
- Faculty
- Course
- Department

---

# 🏫 College Management System Data Model

## Objects
- Student
- Faculty
- Course
- Department

---

## Relationships
- One Department can have many Courses
- One Faculty can teach many Courses
- One Course can have many Students

### Lookup Relationships
- Student → Course
- Course → Faculty
- Course → Department

---

## Diagram / Structure

Department  
↓  
Course  
↓  
Student  

Faculty  
↓  
Course  

---

# 🧮 Formula Fields

## Full Name
Automatically combines first name and last name.

## Percentage
Calculates student percentage automatically.

## Remaining Seats
Calculates available seats in a course.

### Why Formula Fields?
Formula Fields reduce manual work and improve accuracy by automatically calculating values.

---

# ✅ Validation Rules

## Email cannot be empty
Prevents missing student email information.

## Student age cannot be negative
Prevents invalid age values.

## Course seats cannot exceed limit
Prevents overbooking of courses.

### Why Validation Rules?
Validation Rules help maintain correct, accurate, and consistent data.
