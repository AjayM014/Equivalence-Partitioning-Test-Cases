# Equivalence Partitioning Test Cases

## 📌 Overview

This repository contains **Equivalence Partitioning (EP) test case exercises** based on common software input validation scenarios.

Equivalence Partitioning is a **black-box testing technique** that divides input data into different groups called **equivalence classes**. Each class contains inputs that are expected to behave similarly.

## 🎯 Objective

The main objective of this project is to:

* Identify valid and invalid equivalence partitions.
* Select representative test values for each partition.
* Understand input validation using black-box testing.
* Reduce the number of test cases while maintaining effective test coverage.

## 🧪 Exercises Covered

| Exercise | Application          | Requirement             |
| -------- | -------------------- | ----------------------- |
| 1        | Marks Validation     | Marks between 0 and 100 |
| 2        | ATM Withdrawal       | ₹500 to ₹20,000         |
| 3        | Username Validation  | 5 to 15 characters      |
| 4        | Mobile Number        | Exactly 10 digits       |
| 5        | Shopping Cart        | 1 to 10 items           |
| 6        | Bank Account Balance | ₹1,000 to ₹10,00,000    |
| 7        | Employee Salary      | ₹15,000 to ₹2,00,000    |
| 8        | Movie Ticket Booking | 1 to 6 tickets          |

## 📚 Test Scenarios

### 1. Marks Input Validation

**Requirement:** Students can enter marks from 0 to 100.

* Invalid: Less than 0
* Valid: 0–100
* Invalid: Greater than 100

### 2. ATM Withdrawal Validation

**Requirement:** Withdrawal amount must be between ₹500 and ₹20,000.

* Invalid: Below ₹500
* Valid: ₹500–₹20,000
* Invalid: Above ₹20,000

### 3. Username Validation

**Requirement:** Username must contain 5–15 characters.

* Invalid: Less than 5 characters
* Valid: 5–15 characters
* Invalid: More than 15 characters

### 4. Mobile Number Validation

**Requirement:** Mobile number must contain exactly 10 digits.

* Invalid: Less than 10 digits
* Valid: Exactly 10 digits
* Invalid: More than 10 digits

### 5. Shopping Cart Quantity

**Requirement:** Customer can purchase 1–10 items.

* Invalid: Less than 1
* Valid: 1–10
* Invalid: More than 10

### 6. Bank Account Balance

**Requirement:** Minimum balance is ₹1,000 and maximum balance is ₹10,00,000.

* Invalid: Below ₹1,000
* Valid: ₹1,000–₹10,00,000
* Invalid: Above ₹10,00,000

### 7. Employee Salary

**Requirement:** Salary must be between ₹15,000 and ₹2,00,000.

* Invalid: Below ₹15,000
* Valid: ₹15,000–₹2,00,000
* Invalid: Above ₹2,00,000

### 8. Movie Ticket Booking

**Requirement:** Customer can book 1–6 tickets per transaction.

* Invalid: Less than 1 ticket
* Valid: 1–6 tickets
* Invalid: More than 6 tickets

## 🔍 Testing Technique

**Testing Technique:** Equivalence Partitioning
**Testing Type:** Black-Box Testing
**Focus:** Input Validation




## 👨‍💻 Purpose

This project is created for **software testing practice** and demonstrates how Equivalence Partitioning can be applied to real-world input validation requirements.
