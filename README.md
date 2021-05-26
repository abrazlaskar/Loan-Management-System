# Loan-Management-System

This project is a basic loan management system which consists operations for "CUSTOMERS", "ADMIN", and "AGENT". These are the 3 roles that are included in this project. Each role will be defined along with the actions they are allowed to execute. I have used Python for the entire project. The 3 roles are briefly explained below:

1)**CUSTOMERS**
- These individuals are those who have taken loans from the bank and remain as customers until they return the amount they have borrowed from the bank with interest.
- THey are allowed to execute a single action; they can see the details of their own loans using their unique Loan Id assigned to them.

2) **ADMIN**
 This role is assigned to those who work at the bank and are in charge of the follwoing tasks:
- List, View and Edit All Customer records using filters
- Approval of Loan Request made by Customer

3) **AGENT**
This role is assigned to those who work at the bank with the primary responsibility of attracting customers to the bank. They are in charge of the following tasks
-  Ability to list and view loans (approved) or loan requests 
-  Create a loan request on behalf of the user
-  Edit Customer Records but only before the approval of the Admin
-  View All Customer Records using filters

There are 3 jupyter notebooks which are named as **CUSTOMERS**,**ADMIN** and **AGENT**. Each notebook consists of Python code which allows for executing actions assigned to each user role. Every piece of information is recorded and added to a separate SQL database. Customer details can be added, removed and updated according to user- defined actions.


** Incase the jupyter noteboos are not loading on your screen, please visit the follwoing alternative links to access the code**

**ADMIN CODE LINK**  https://nbviewer.jupyter.org/github/abrazlaskar/Loan-Management-System/blob/main/ADMIN.ipynb

**AGENT CODE LINK**    https://nbviewer.jupyter.org/github/abrazlaskar/Loan-Management-System/blob/main/AGENT.ipynb

**CUSTOMER CODE LINK**  https://nbviewer.jupyter.org/github/abrazlaskar/Loan-Management-System/blob/main/CUSTOMER.ipynb
