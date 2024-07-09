# MotorPH Payroll System Database

## Table of Contents
1. [Introduction](#introduction)
2. [Database Tables](#database-tables)
    - [Allowance](#allowance)
    - [Deduction](#deduction)
    - [Department](#department)
    - [Employee](#employee)
    - [Leave Request](#leave-request)
    - [Leave Request Category](#leave-request-category)
    - [Payslip](#payslip)
    - [Permission](#permission)
    - [Position](#position)
    - [Role](#role)
    - [Tax](#tax)
    - [Tax Category](#tax-category)
    - [Timesheet](#timesheet)
    - [User](#user)
3. [Queries](#queries)
    - [Payslip Query](#payslip-query)
    - [Monthly Payroll Summary Query](#monthly-payroll-summary-query)
4. [Testing](#testing)
5. [Images and Videos](#images-and-videos)

## Introduction
The MotorPH Payroll System Database manages employee information, payroll, and related data efficiently. This README provides an overview of database tables, queries, testing procedures, and includes images and videos.

## Database Tables

### Allowance
Table for managing allowances given to employees.
![Allowance](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/77c5233b-d96c-420d-9f54-3aba1b2a6479)
Description: Manages various types of allowances provided to employees.

### Deduction
Table for managing deductions from employee salaries.
![Deduction](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/3c7a8231-baf3-4010-b523-ece48dd4e853)
Description: Tracks deductions made from employee salaries, such as taxes and contributions.

### Department
Table for storing department information within MotorPH.
![Department](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/bd15f55a-de34-4733-ace6-1d911f39d438)
Description: Stores details about different departments in MotorPH.

### Employee
Table containing details of each employee in MotorPH.
![Employee](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/b791613a-96bf-483b-a561-30e4999138c3)
Description: Holds comprehensive information about each employee at MotorPH, including personal and employment details.

### Leave Request
Table for tracking leave requests submitted by employees at MotorPH.
![Leave Request](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/c2706c21-3249-4b64-84f5-19d98db95117)
Description: Records details of leave requests made by employees at MotorPH, including type and duration.

### Leave Request Category
Table categorizing different types of leave requests at MotorPH.
![Leave Request Category](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/2d0647c9-2f87-4a94-bea1-c116e2a75a44)
Description: Categorizes various types of leave available to employees at MotorPH.

### Payslip
Table containing detailed pay information for each employee at MotorPH.
![Payslip](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/b17d6012-749f-4a5a-a521-d52e2e4c2072)
Description: Provides detailed breakdowns of employees' earnings and deductions for each pay period at MotorPH.

### Permission
Table specifying permissions granted to users within MotorPH.
![Permission](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/022fd002-15f8-4153-8833-7c1c52be7dd1)
Description: Defines the access rights and privileges granted to different users within MotorPH.

### Position
Table storing different job positions available at MotorPH.
![Position](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/34548403-e6a0-454f-a2aa-a21532d6aa7d)
Description: Lists the various job positions within MotorPH.

### Role
Table defining roles and responsibilities assigned to employees at MotorPH.
![Role](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/29cdae42-d414-4515-983a-18ee2f18387b)
Description: Specifies the roles assigned to employees at MotorPH, governing their responsibilities and permissions.

### Tax
Table for managing tax-related information for payroll processing at MotorPH.
![Tax](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/17365e3b-3326-4da5-9f02-aacdb1dfb88a)
Description: Stores tax-related details used in calculating employees' tax deductions at MotorPH.

### Tax Category
Table categorizing different tax types at MotorPH.
![Tax Category](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/899b058f-97d0-465e-8d29-b89d7052438f)
Description: Categorizes various tax types applicable to employees' earnings at MotorPH.

### Timesheet
Table recording hours worked by employees at MotorPH.
![Timesheet](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/53fc95d0-7a45-48d2-bb5a-4756aada631a)
Description: Logs the hours worked by each employee on a daily basis at MotorPH.

### User
Table storing user credentials and access information at MotorPH.
![User](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/ddc2d22e-7e7c-472f-944d-a97adae9a06b)
Description: Manages user credentials and access rights within the payroll system at MotorPH.

## Queries

### Payslip Query
```sql
-- Sample Payslip Query
SELECT * FROM payslip WHERE employee_id = 'example_id';

