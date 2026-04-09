# Student-Enrollment.py📘 Student Enrollment Script
A simple Python script that simulates the role of a University Registrar enrolling a new student into a university system.
This project demonstrates basic Python variable types, formatted output, and memory cleanup.

🎯 Objective
Create a Python script (enrollment.py) that stores student information, prints a formatted enrollment report, and simulates closing a financial transaction by deleting a variable.

🛠️ Step-by-Step Instructions
1. Environment Check
Before writing any code, confirm that Python is installed on your system:

bash
python --version
You should see a version number such as Python 3.x.x.

2. Create the Script File
Create a new file named:

Code
enrollment.py
Inside this file, define variables representing a student’s profile using the required data types:

Field	Data Type	Example
First Name	String (double quotes)	"John"
Last Name	String (single quotes)	'Doe'
Age	Integer	20
Tuition Balance	Float	15230.75
Is Active	Boolean	True

3. Generate the Enrollment Report
Use print() and f‑strings to display a clean, readable report.
The report should include all student information in a professional format.

Example output structure:

Code
===== Student Enrollment Report =====
First Name: John
Last Name: Doe
Age: 20
Tuition Balance: $15230.75
Active Status: True
=====================================
4. Clean Up (Variable Deletion)
At the end of the script, use:

python
del tuition_balance
This simulates closing the financial transaction by removing the tuition balance from memory.