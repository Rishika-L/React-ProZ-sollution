1.Employee APIs
---------------

Create Employee
POST /api/employees

Get All Employees
GET /api/employees  

Get Employee by ID
GET /api/employees/:id

Update Employee
PUT /api/employees/:id

Delete Employee
DELETE /api/employees/:id

2.Designation APIs
-------------------

Add Designation
POST /api/designations

Get All Designations
GET /api/designations

Update Designation
PUT /api/designations/:id

Delete Designation
DELETE /api/designations/:id

3.Attendance APIs
-----------------
Mark Attendance
POST /api/attendance

Get All Attendance
GET /api/attendance

Employee-wise Attendance
GET /api/attendance/employee/:employeeId

Date Attendance
GET /api/attendance/date/2026-01-12

Update Attendance
PUT /api/attendance/:id

4.Task APIs
-----------

POST /api/tasks

GET /api/tasks

Employee Tasks
GET /api/tasks/employee/:employeeId

Update Task Status
PUT /api/tasks/:id

Delete Task
DELETE /api/tasks/:id

5.Status APIs
-------------

Get All Status
GET /api/status

Add Status
POST /api/status
