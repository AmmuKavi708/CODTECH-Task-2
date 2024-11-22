Name:KAVITHA S 
Company:CODETECH IT SOLUTIONS 
ID:CT08DS10164 
Domain:Python Programming 
Duration: November 15th,2024 to December 15th,2024 
Mentor:NEELA SANTHOSH KUMAR

Overview of the Student Grades Management Project
        This Python project is designed to efficiently track and manage student grades. It allows users (such as teachers or students) to input grades for various subjects or assignments, calculate the average grade, and display performance metrics like overall grade and letter grades.
Objective
The primary goal of this project is to:
      1. Streamline grade tracking for students in multiple subjects or assignments.
      2. Provide real-time insights into overall academic performance using numerical and letter grades.
      3. Serve as an easy-to-use and interactive system for educational purposes.
Key Features
1. Grade Entry:
      Allows users to add grades for specific subjects or assignments.
      Ensures grades are numeric and within a valid range (0–100).
      Provides the ability to overwrite existing grades for a subject.

2. Grade Display:
      Lists all entered grades for the student.
      Displays the average grade across all subjects.

Converts the numerical average to a letter grade:
A: 90–100
B: 80–89
C: 70–79
D: 60–69
F: Below 60

3. Average Grade Calculation:
      Automatically calculates the average of all grades entered.

4. Interactive Menu:
      Provides a simple and intuitive interface with options to:

   Add a grade.

Display grades and overall performance.

Exit the program.


Project Workflow
1. Input Grades:
      The user enters grades by providing the subject name and the grade value.
      The system validates the grade to ensure it’s between 0 and 100.

2. Calculate Performance:
      The system computes the average grade and determines the corresponding letter grade.

3. Display Results:
      Users can view a summary of all entered grades, the average grade, and the final letter grade.

4. Exit:
      The user can terminate the program gracefully.


Technical Highlights

1. Python Programming Concepts Used:
      Classes and Objects: To encapsulate grade-related operations.
      Static Methods: For letter grade determination based on averages.
      Error Handling: Ensures user inputs are valid and prevents program crashes.
      Loops and Conditionals: To provide a simple interactive menu.

2. Code Modularity:
      Organized into methods for specific tasks (e.g., adding grades, calculating averages).
      Easy to expand for additional features like saving/loading grades from files.


Potential Enhancements
1. Persistent Storage:
      Save grades to a file or database for future retrieval.
2. Multi-Student Support:
      Extend the program to manage grades for multiple students.
3. Detailed Reporting:
      Add features to generate detailed performance reports for students.
4. Integration with UI Frameworks:
      Create a graphical user interface (GUI) using libraries like Tkinter or PyQt for ease of use.

Applications
1. Academic Tracking:
      Ideal for teachers to manage class grades and performance.
2. Student Use:
      Helps students track their academic progress in real time.
3. Learning Tool:
      Demonstrates fundamental programming concepts for beginners in Python.

This project combines functionality, simplicity, and scalability, making it a versatile solution for managing student grades.

Sample Input and Output:
Grade Manager

1. Add Grade

2. Display Grades

3. Exit

Choose an option: 1

Enter subject name: maths 

Enter grade for maths : 80

Grade added: maths  - 80.0



Grade Manager

1. Add Grade

2. Display Grades

3. Exit

Choose an option: 2



Student Grades:

maths : 80.0

Average Grade: 80.00

Letter Grade: B



Grade Manager

1. Add Grade

2. Display Grades

3. Exit

Choose an option: 3

Exiting...
