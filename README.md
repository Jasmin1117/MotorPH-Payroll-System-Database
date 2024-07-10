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
3. [Views](#views)
    - [Department Monthly Payroll Report](#department-monthly-payroll-report)
    - [Employee Allowance Cost](#employee-allowance-cost)
    - [Employee Monthly Hours Worked](#employee-monthly-hours-worked)
    - [Employee Timesheets](#employee-timesheets)
    - [Monthly Payroll Report](#monthly-payroll-report)
    - [Timesheet Summary](#timesheet-summary)
4. [Queries](#queries)
    - [Payslip Query](#payslip-query)
    - [Monthly Payroll Summary Query](#monthly-payroll-summary-query)
6. [Testing](#testing)

---

## Introduction
The MotorPH Payroll System Database manages employee information, payroll, and related data efficiently. This provides an overview of database tables, queries, testing procedures, and includes images and videos.

### Database Script

You can download the database script [here](https://drive.google.com/file/d/10YCYOxMhlvqPf699g-ONtNyx8cul_5QK/view?usp=sharing).

## Database Tables

### Allowance
Table for managing allowances given to employees.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/77c5233b-d96c-420d-9f54-3aba1b2a6479" alt="Allowance" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/1679c5ae-28b1-4325-8b70-c3fb2f48d33b" alt="Allowance" width="500">

### Deduction
Table for managing deductions from employee salaries.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/3c7a8231-baf3-4010-b523-ece48dd4e853" alt="Deduction" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/e5d0e224-54f8-46d3-a789-59cc6d6250c6" alt="Deduction" width="500">

### Department
Table for storing department information within MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/bd15f55a-de34-4733-ace6-1d911f39d438" alt="Department" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/7d79ec3c-ef85-44e9-9319-369adb963601" alt="Department" width="500">

### Employee
Table containing details of each employee in MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/b791613a-96bf-483b-a561-30e4999138c3" alt="Employee" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/f305ae5e-d41c-4567-a73b-52d0ffa1307f" alt="Employee" width="500">

### Leave Request
Table for tracking leave requests submitted by employees at MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/c2706c21-3249-4b64-84f5-19d98db95117" alt="Leave Request" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/90d5f7f7-d5c2-473e-96b3-031350006e75" alt="Leave Request" width="500">

### Leave Request Category
Table categorizing different types of leave requests at MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/2d0647c9-2f87-4a94-bea1-c116e2a75a44" alt="Leave Request Category" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/3fdc74aa-0846-457b-84c1-002e4b1450f2" alt="Leave Request Category" width="500">

### Payslip
Table containing detailed pay information for each employee at MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/b17d6012-749f-4a5a-a521-d52e2e4c2072" alt="Payslip" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/e9258920-94c1-457c-9a04-bd9f59861d74" alt="Payslip" width="500">

### Permission
Table specifying permissions granted to users within MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/022fd002-15f8-4153-8833-7c1c52be7dd1" alt="Permission" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/1f358b7c-485e-475b-83bd-e6ca54097474" alt="Permission" width="500">

### Position
Table storing different job positions available at MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/34548403-e6a0-454f-a2aa-a21532d6aa7d" alt="Position" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/ef1abe73-818e-4aaf-9457-c57419f81d5f" alt="Position" width="500">

### Role
Table defining roles and responsibilities assigned to employees at MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/29cdae42-d414-4515-983a-18ee2f18387b" alt="Role" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/da534007-fa55-4774-b00f-91ae8dda2ba7" alt="Role" width="500">

### Tax
Table for managing tax-related information for payroll processing.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/17365e3b-3326-4da5-9f02-aacdb1dfb88a" alt="Tax" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/4270c290-7d89-4827-95e9-07571376e80d" alt="Tax" width="500">

### Tax Category
Table categorizing different tax types at MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/899b058f-97d0-465e-8d29-b89d7052438f" alt="Tax Category" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/c3f921f7-6ca7-4607-a432-2dc74b176955" alt="Tax Category" width="500">

### Timesheet
Table recording hours worked by employees at MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/53fc95d0-7a45-48d2-bb5a-4756aada631a" alt="Timesheet" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/367943e5-caac-4a5e-9cf0-9aab8caacf82" alt="Timesheet" width="500">

### User
Table storing user credentials and access information at MotorPH.
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/ddc2d22e-7e7c-472f-944d-a97adae9a06b" alt="User" width="300">

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/57790b82-c5b6-42cf-a7bc-1b05942ff1be" alt="User" width="500">

---

## Views

### Department Monthly Payroll Report
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/17fe480b-0e08-490f-bffc-19bdba7b14c3" alt="Department Monthly Payroll Report" width="500">

### Employee Allowance Cost
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/3dc6bf4d-cbc6-430f-aa01-b92fc15ee8a9" alt="Employee Allowance Cost" width="500">

### Employee Monthly Hours Worked
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/6b028e9a-ed29-446d-8e6f-f5dc33e243c6" alt="Employee Monthly Hours Worked" width="500">

### Employee Timesheets
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/36e22b7e-1ca6-4268-bb12-181f30f2aeda" alt="Employee Timesheets" width="500">

### Monthly Payroll Report
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/9896f2bf-2ebb-44fa-b45a-9d5873a37ecb" alt="Monthly Payroll Report" width="500">

### Timesheet Summary
<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/65e08987-db2d-456b-8e92-6912047d7e63" alt="Timesheet Summary" width="500">

---

## Queries

### Payslip Query
The following SQL query calculates payslip details including regular hours worked, overtime hours, and benefits for active employees within a specified date range:

![Image_20240710_005231_296](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/419a6c80-f78d-4ca1-a510-ec511e900e9a)
You can download the database script [here](https://drive.google.com/file/d/1_a4z3QLvy0THBQSV5yqPnps4HyoE1fA4/view?usp=sharing).

This query retrieves detailed payslip information for active employees, including regular and overtime hours worked, salary calculations based on hourly rates, and benefits such as rice subsidy, clothing allowance, and phone allowance. The results are grouped by employee and include their department and position within the MotorPH organization.

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/9b911b4f-794a-43a4-aa6b-2553f96369b4" alt="payslipquery" width="500">

Replace ? in the BETWEEN ? AND ? clause with specific date parameters when displaying the payslip. This query provides essential data for payroll processing and analysis within the MotorPH Payroll System.

### Payroll Summary Query
The following SQL query summarizes payroll details including gross income, deductions, contributions, withholding tax, and net pay for each employee at MotorPH:

<img src="https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/8d6d9182-dcd6-43ff-af32-86669a397014" alt="payrollsummary" width="700">
You can download the database script [here](https://drive.google.com/file/d/14JL09PuCEydXFYFIDr0xbZgkXHg27Pnv/view?usp=sharing).

This query calculates essential payroll details such as gross income, social security contributions, Philhealth contributions, Pag-ibig contributions, TIN, withholding tax, and net pay for each employee at MotorPH. It provides comprehensive information needed for payroll processing and reporting within the organization.

![payrollsummarys](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/3b47c5bb-04da-496c-bbd8-f598f81e0513)

---

## Testing

### Create Employee Record

**Actions**  
Write a query that will insert the following employee records into the database:
- Billy Lloyd Calasang
- Jonathan Brosas
- Shella Mae Tejor

**Actual Result**  
The employee records are successfully stored in the database.

![sss](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/960f140b-5655-46ab-bb56-cd4839427427)

---

### Update Employee Information

**Actions**  
Write a query that will display the following employee records:
- Carlos Ian Martinez
- Beatriz Santos
- John Rafael Castro
- Shella Mae Tejor

Update the fields related to salary information based on the gross salary provided below:
- Carlos Ian Martinez - 23,000
- Beatriz Santos - 25,000
- John Rafael Castro - 23,000
- Shella Mae Tejor - 25,000

**Actual Result**  
The correct employee data records are retrieved and updated accurately.

![updateddd](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/1a1d8349-ce7e-4940-9fc4-e1ca10f23804)

---

### Delete Employee Record

**Actions**  
Write a query that will delete the following employee records from the database:
- 34 - Carol Ramos
- 35 - Emelia Maceda
- 36 - Delia Aguilar

**Actual Result**  
The employee records for Carol Ramos, Emelia Maceda, and Delia Aguilar were successfully deleted from the database.

![MySQLWorkbench_0lshnZFJ5R](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/7c0b7381-308b-4c4b-bb4b-f72966a9ffbd)

---

### Check Employee ID Uniqueness

**Actions**  
Attempt to add a new employee record:
- Mac Arnold Almirol

**Actual Result**  
The database rejected the addition of the new employee record and displayed an error message indicating the violation of the unique constraint for Employee IDs.

![result](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/adbacece-0b36-4d7b-95d2-117ff9481fb1)

---

### Check Null Values

**Actions**  
Attempt to add a new employee record with the following information:
- Employee Name: Harold Ian Correa
- Birthdate: December 16, 1996
- Address: 8435 West Service RoadMarcelo Green Village South Superhighway, Paranaque City

**Actual Result**  
The database rejected the addition of the new employee record and displayed the error message below:

![ff](https://github.com/Jasmin172002/MotorPH-Payroll-System-Database/assets/125138169/33a4fd31-c416-4709-a360-5e283c9c06cb)

