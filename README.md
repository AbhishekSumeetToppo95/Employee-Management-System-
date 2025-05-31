# Employee-Management-System-

📘 Employee Management System – C++ Console Application
🧩 Project Overview
The Employee Management System is a console-based application developed in C++ that allows administrators to manage employee data efficiently. It includes essential CRUD operations — Create, Read, Update, and Delete — along with login authentication and a user-friendly interface.

🛠️ Features Implemented
🔐 User Authentication
Implemented a basic signup and login system using username and password validation, enhancing access control for system usage.

🗂️ Employee Data Management

Add multiple employees with structured data (name, ID, address, contact, salary).

Display all stored employee records in a formatted view.

Search for employees by their ID.

Update an existing employee's data.

Delete a specific record or clear all employee records.

💡 Menu-Driven Interface
Interactive user interface using getch() and switch-case, enabling smooth navigation between system functions.

⚙️ Console Enhancements
Used windows.h and conio.h to incorporate delays (Sleep()), character input (getch()), and screen clearing (system("CLS")) for a better user experience.

🏗️ Technical Details
Language: C++

Compiler: Turbo C++ / Dev C++ / Code::Blocks (with Windows support)

Libraries Used:

<iostream> – Input/output operations

<conio.h> – Console I/O (getch, clrscr)

<windows.h> – Sleep and screen control

Data Structure:
Used a structure (struct emp) to store employee attributes and a fixed-size array (emp e[100]) to manage up to 100 employees.
