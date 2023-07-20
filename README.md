# SAP-ABAP-PROJECT-002-
SCREEN EMPLOYEES [MODULE POOL PROGRAM]

Project: Employee Login and Registration Screen in SAP ABAP

Objective:
The objective of this project is to develop a system in SAP ABAP that allows company employees to access a login screen and, upon successful authentication, gain access to an employee registration screen. Additionally, the system should enable the registration of new employees, display previously registered employees, and limit login attempts to three in case of authentication failure.

Specifications:

Login Screen:

The login screen should have fields for "Username" and "Password."
The system should allow a maximum of three login attempts.
In case of authentication failure, display a message indicating the remaining number of attempts.
After successful login, redirect the user to the employee registration screen.
Employee Registration Screen:

The employee registration screen should have the following fields: Name, Position, Date of Birth, and Department.
The system should validate whether all mandatory fields have been filled before saving the registration.
Upon successful registration, display a confirmation message and clear the fields for a new registration.
Display of Registered Employees Screen:

List all previously registered employees on the display screen.
Allow the selection of a specific employee to view their details.
Include a button or option to return to the employee registration screen.
Navigation Flow:

The user should start the application, being directed to the login screen.
After successful authentication, the user will be redirected to the employee registration screen.
On the registration screen, the user can add new employees and view the previously registered ones.
On the display screen, the user can return to the registration screen to add new employees.
Security:

Ensure that all passwords are stored securely and encrypted.
Implement measures to protect against brute-force attacks on the login screen (temporary lockout after multiple failed attempts).
User Interfaces:

Develop user-friendly and intuitive screens to facilitate usability.
Use clear and informative messages to guide the user during the login and registration process.
