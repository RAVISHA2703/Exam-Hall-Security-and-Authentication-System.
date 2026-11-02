# Exam-Hall-Security-and-Authentication-System.
 **Main** **features**: Register student examination details. Authenticate students using their roll number and exam registration details. Verify whether a student is assigned to the exam. Check exam hall and seat allocation. Prevent duplicate entry records. Record successful and rejected authentication attempts. Display student verification.
**The program follows this sequence**:
1)Register Student — Save the student's name, roll number, exam code, hall, and seat.
2) Authenticate Student — Check the roll number and exam registration code.
3) Verify Eligibility — Check whether the student is eligible and has already entered.
4) Confirm Documents — The invigilator manually checks the official admit card and photo ID.
5) Record Entry — Save the successful entry and timestamp.
6)Check Hall Status — Display assigned candidates and recorded entries.
7) View Entry Log — Review accepted, rejected, and pending attempts.

**CONCEPTS USED**
Concepts Used in the Project
1
Basic Input/Output
printf(), fgets()
To display the menu and accept user input.
2
Variables and Data Types
int, char, size_t
To store student details, choices, and status.
3
Structures (struct)
typedef struct { ... } Student;
To store all details of a student in one record.
4
Arrays
Student students[MAX_STUDENTS];
To store records of multiple students.
5
Strings
name, roll, examCode, hall, seat
To store and process student information.
6
Functions
registerStudent(), authenticateStudent()
To divide the program into smaller, reusable modules.
7
Conditional Statements
if, else, switch
To check eligibility, validate details, and select menu options.
8
Loops
for, do-while
To search student records, display students, and repeat the menu.
9
String Handling
strcmp(), strlen()
To compare roll numbers and exam registration codes and process input.
10
Searching
findStudentByRoll()
To find a student using their roll number.
11
File Handling
fopen(), fprintf(), fgets(), fclose()
To save and retrieve student records and entry logs.
12
File-Based Data Persistence
saveStudents(), loadStudents()
To retain student records after the program closes.
13
Pointers
Student *s = &students[index];
To access and update the selected student's record.
14
User-Defined Functions
showMenu(), saveStudents(), logAttempt()
To make the program modular and easier to maintain.
15
Authentication Logic
authenticateStudent()
To check the roll number, registration code, and eligibility.

**PROJECT STRUCTURE:-
exam-hall-security-system/
│
├── project.c
│
├── README.md
│
├── .gitignore
│
├── students.dat
│
└── entry_log.txt
**

**POSSIBLE IMPROVEMENT**:-
1) Admin Login System: Add secure administrator authentication so only authorized staff can register students and manage examination records.
2) QR Code Verification: Generate a unique QR code for each student's admit card to make record verification faster.
3) Biometric Authentication: Integrate institution-approved fingerprint or facial verification hardware and software, with appropriate consent and privacy safeguards.

**AUTHOR**
    RAVISHA SHEOKAND
