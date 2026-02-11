# STUDENT GRADE MANAGEMENT SYSTEM
-------------------------------------

This is a C# console application that allows users to manage student academic records through an interactive menu system.
What it does:

Adds students with unique names and IDs to the system
Records grades for multiple subjects per student
Automatically calculates average grades for any student
Displays comprehensive records showing all students, their subjects, grades, and averages
Validates all user inputs to prevent errors (checks for duplicate IDs, ensures grades are 0-100, handles empty entries)

Technical Implementation:-
The program uses object-oriented programming with a Student class to store data. It demonstrates key programming concepts including:

Switch statements for menu navigation
If-else conditions for data validation
While loops to keep the program running
For loops to iterate through student lists
Custom methods like CalculateAverage() to perform calculations
Data structures (Lists and Dictionaries) to organize information efficiently

User Experience:
Users interact with a simple numbered menu where they can add students, assign grades, calculate averages, view all records, or exit the program. The system provides clear feedback with success messages (✅) and error alerts (❌) to guide users through each operation.
This project demonstrates fundamental programming skills needed for real-world application development...

Move to directory `cd Students`

Run code with `dotnet run`

should display this output 👇👇
========================================
   STUDENT GRADE MANAGEMENT SYSTEM
========================================

========================================
         MENU OPTIONS:
========================================
1. Add New Student
2. Add Grade to Student
3. Calculate Student Average
4. Display All Students
5. Exit
===================================
Enter your choice:
