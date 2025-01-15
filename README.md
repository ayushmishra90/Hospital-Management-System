# Hospital Management System

## Overview
The Hospital Management System is a C++ application designed using Object-Oriented Programming (OOP) principles. This system facilitates the management of doctor and patient records, enabling users to:

- Add, view, and manage doctor records.
- Add, view, and manage patient records.
- Check doctor availability.
- Secure the application using a password-based authentication mechanism.

This program is an efficient tool for maintaining a hospital's operational data, providing seamless access and organization.

---

## Workflow
### Welcome Screen
```
WELCOME TO IIITDMK HOSPITAL MANAGEMENT SYSTEM

------------------------------------------------     
     1. Main Menu
     2. Create User
     3. Exit
------------------------------------------------
```
### Main Menu
```
--------------------------------------------------------------------------------
     1. Enter Into Doctors' Database
     2. Enter Into Patients' Database
     3. Check for Hospital Bed Availability
     4. Exit
--------------------------------------------------------------------------------
```
Users navigate the system using the numbered options.

### Authentication
- The system prompts for a username and password.
- Example:
```
Enter username: Ayush
Enter the password: 123
```

### Doctor Management
```
WELCOME TO DOCTOR'S DATABASE

1. Add New Doctor's Information
2. Edit a Doctor's Information
3. Display a Doctor's Information
4. Delete a Doctor's Information
5. Display Entire Doctor Database
6. Total Number of Doctors
7. Exit
--------------------------------------------------------------------------------
```
Users can manage doctor records efficiently by selecting options from this menu.

### Patient Records
Patient records are stored in `patient.txt`. Example:
```
ID: 102
Name: Anish Bengali
Age: 25
Contact: 826563800
Address: Kolkata
Illness: HIV
Admission Date: 01/01/2023
Discharge Date: 01/01/2024
```

### Doctor Records
Doctor records are stored in `doctor.txt`. Example:
```
1. Ashu Mishra, 20, MD, NEUROLOGY, Kanpur
2. Ravi Yadav, 20, MBBS, GENERAL_MEDICINE, Varanasi
```

Passwords for authentication are stored in `password.txt`. Example:
```
Ayush,123
Ravi,122
Harsh,124
Ashu,123
```

---

## Requirements
To run this application, ensure your system meets the following requirements:

- A C++ compiler (e.g., GCC, Clang, or MSVC).
- C++17 or later support.
- An IDE or text editor (e.g., VS Code, CLion, Code::Blocks) for running the program.

---

## Installation and Execution
Follow these steps to run the Hospital Management System on your system:

1. **Clone or Download the Repository**
   - Clone the repository using Git:
     ```bash
     git clone https://github.com/ayushmishra90/Hospital-Management-System
     ```
   - Alternatively, download the ZIP file and extract it.

2. **Navigate to the Directory**
   ```bash
   cd Hospital-Management-System
   ```

3. **Compile the Code**
   - Use your preferred C++ compiler to compile the code. For example, with GCC:
     ```bash
     g++ -std=c++17 hospital_management.cpp -o hospital_management
     ```

4. **Run the Application**
   - Execute the compiled program:
     ```bash
     ./hospital_management
     ```

5. **Use the Application**
   - Follow the prompts to interact with the Hospital Management System.

---

## Features
- Password-protected access.
- User-friendly interface.
- Comprehensive management of doctor and patient records.
- Real-time doctor availability checks.
- Modular and scalable code.

---

## Future Enhancements
Potential improvements for the system:

- Integration with a database for persistent storage.
- Implementation of a graphical user interface (GUI).
- Additional features such as appointment scheduling and billing.

---

## Troubleshooting
- **Compilation Errors:** Ensure your C++ compiler supports C++17 or later.
- **Execution Issues:** Verify file permissions and correct compilation of the source code.

---

## Author
Developed by an enthusiastic Computer Science and Engineering student at IIIT Kurnool, leveraging OOP principles to create practical and efficient software solutions.

---

## Presentation
The project repository includes a presentation file named `hospital_management_presentation.pptx`. This presentation highlights the key features, workflows, and technical details of the Hospital Management System. 

To access the presentation:

1. Clone the repository:
   ```bash
   git clone https://github.com/ayushmishra90/Hospital-Management-System
   ```
2. Navigate to the project directory and open `hospital_management_presentation.pptx` using any compatible software, such as PowerPoint, Google Slides, or Keynote.
3. 

