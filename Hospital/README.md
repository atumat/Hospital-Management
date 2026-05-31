# Hospital Management System (C++)

## Overview

This project is a console-based Hospital Management System developed in C++. The application simulates various hospital operations such as patient admission, employee salary management, pharmacy calculations, billing, scan selection, and cafeteria services.

The primary objective of the project is to demonstrate Object-Oriented Programming (OOP) concepts in C++ through a hospital-themed application.

---

## Features

### 1. Patient Admission Management

* Admit new patients.
* Store patient details including:

  * Name
  * Age
  * Patient ID
* View patient information using Patient ID.
* Track available hospital capacity.

### 2. Employee Management

* Register employee details.
* Support multiple employee categories:

  * Doctor
  * Admin
  * Housekeeping
  * Maintenance
* Calculate monthly salary based on employee type and hours worked.

### 3. Pharmacy Module

* Calculate total supplier cost of tablets.
* Calculate total supplier cost of vials.
* Demonstrates function overloading.

### 4. Billing Module

* Calculate charges for:

  * General Ward stay
  * ICU stay
* Generate combined patient bill.
* Demonstrates operator overloading.

### 5. Scan Department

* Display available imaging services:

  * X-Ray
  * MRI
  * CT Scan
* Display estimated scan duration.
* Allow scan selection.

### 6. Cafeteria Module

* Order food and beverages.
* Supported items:

  * Tea
  * Coffee
  * Sandwich
  * Cookie
* Calculate final cafeteria bill.

---

## Project Flow

```text
Start
  |
  v
Patient Admission System
  |
  +--> Add Patient
  |
  +--> View Patient Details
  |
  v
Employee Management
  |
  +--> Enter Employee Details
  +--> Calculate Salary
  |
  v
Pharmacy Module
  |
  +--> Tablet Cost Calculation
  +--> Vial Cost Calculation
  |
  v
Billing Department
  |
  +--> General Ward Charges
  +--> ICU Charges
  +--> Total Bill Generation
  |
  v
Scan Department
  |
  +--> View Scan Types
  +--> Select Scan
  |
  v
Cafeteria
  |
  +--> Order Food Items
  +--> Generate Food Bill
  |
  v
End
```

---

## Class Structure

```text
hospital
   |
   v
info
   |
   +------> patient
   |
   +------> employee

scan
   |
ptime
   |
   v
scantime
```

---

## OOP Concepts Demonstrated

| Concept                   | Implementation                          |
| ------------------------- | --------------------------------------- |
| Classes and Objects       | hospital, patient, employee, bill, cafe |
| Inheritance               | patient → info → hospital               |
| Multiple Inheritance      | scantime inherits scan and ptime        |
| Constructors              | All major classes                       |
| Function Overloading      | add(int,int), add(float,float)          |
| Function Overriding       | display() methods                       |
| Static Members            | hospital capacity                       |
| Friend Function           | calcsal(employee&)                      |
| Virtual Functions         | display() in typesalthree               |
| Runtime Polymorphism      | Base pointer referencing derived object |
| Operator Overloading      | bill + bill                             |
| Dynamic Memory Allocation | new cafe, delete cafe                   |
| Inline Functions          | Welcome message functions               |
| this Pointer              | Parameterized bill constructor          |

---


---























The key ideas that were  referred are  the pillars of OOPs. The foundation of OOP consists of four pillars.


<h3>Abstraction</h3>
The idea enables us to present the user only the most important information while hiding the implementation from them. Using the concept, developer updates  quickly over time.

<h3>Encapsulation</h3>
We may tie the data and functions of a class into an object via encapsulation. It shields information and operations against tampering and manipulation from outside entities. As a result, it also offers security. The finest illustration of encapsulation is a class.


<h3>Inheritance</h3>
The concept allows us to inherit or acquire the properties of an existing class (parent class) into a newly created class (child class). It is known as inheritance. It provides code reusability.

<h3>Polymorphism</h3>
Poly and morphs are the two terms from which the word polymorphism is formed. Both poly and morphs refer to forms. It enables us to design methods that share a name but have various method signatures. It enables the developer to produce code that is clear, logical, legible, and robust.
